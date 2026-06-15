---
name: kb-cloud-skills
description: Execute real operations against the KubeBlocks Cloud API. Use this skill when users need to query, create, modify, or delete KubeBlocks Cloud resources.
metadata:
  author: apecloud
---

# KubeBlocks Cloud Operations Skill

Execute real operations against the KubeBlocks Cloud API using DigestAuth. This skill teaches the agent how to authenticate, navigate the reference docs, construct curl commands, and present results.

## Reference docs structure

This project includes auto-generated API reference docs:

```
references/
├── openapi/           # User-facing API (/api/v1/)
│   ├── resources/     # 77 resource index files
│   ├── operations/    # 720 operation detail files
│   └── schemas/       # 572 schema groups
└── adminapi/          # Admin-facing API (/admin/v1/)
    ├── resources/     # 88 resource index files
    ├── operations/    # 851 operation detail files
    └── schemas/       # 669 schema groups
```

Navigation order: resource → operation → schema. Start from the resource list below, find the operation you need, then read schemas for request/response details.

## Platform overview

KubeBlocks Cloud is a cloud-native database management platform supporting multiple database engines (MySQL, PostgreSQL, Redis, MongoDB, Kafka, etc.).

**Core concepts:**
- **Organization**: top-level namespace for resources
- **Cluster**: a database cluster, the primary management unit
- **Engine**: database engine type (e.g. MySQL, PostgreSQL)
- **Environment**: deployment environment (e.g. dev, prod, staging)
- **Component**: a component within a cluster (e.g. a MySQL pod group)

## The two APIs

| API | Prefix | Purpose | Typical resources |
|-----|--------|---------|-------------------|
| openapi | `/api/v1/` | User-facing, manage database resources | cluster, backup, account, restore, kafka, redis... |
| adminapi | `/admin/v1/` | Admin-facing, manage platform config | environment, engine, organization, SLA, pricing... |

## Environment variables

Before any operation, verify these environment variables are set:

| Variable | Description |
|----------|-------------|
| `KB_CLOUD_BASE_URL` | API base URL |
| `KB_CLOUD_ACCESS_KEY` | API accessKey (get it from **Personal Settings → API Keys**) |
| `KB_CLOUD_SECRET_KEY` | API secretKey (get it from **Personal Settings → API Keys**) |

If any are missing, prompt the user to set them:
```bash
export KB_CLOUD_BASE_URL="YOUR_BASE_URL"
export KB_CLOUD_ACCESS_KEY="YOUR_ACCESS_KEY"
export KB_CLOUD_SECRET_KEY="YOUR_SECRET_KEY"
```

## Agent workflow

Follow these steps for every user request:

### Step 0: Determine API key type (once per session)

**This step is critical** — getting it wrong means all subsequent operations will fail.

Determine whether the key is an **admin key** or a **user key** by probing in order:

**1. Probe `/admin/v1/user` first:**

```bash
curl -s -o /dev/null -w "%{http_code}" --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/admin/v1/user"
```

- **200** → Admin key. Use **adminapi** (`/admin/v1/`). Done — skip step 2.
- **Not 200** → Proceed to step 2.

**2. Probe `/api/v1/user` (only if step 1 was not 200):**

```bash
curl -s -o /dev/null -w "%{http_code}" --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/api/v1/user"
```

Each command outputs a single number (e.g. `200`, `401`). No parsing needed. The `-o /dev/null -w "%{http_code}"` flags ensure only the final HTTP status is printed — DigestAuth's challenge-response 401 is hidden by curl's automatic retry.

**Decision table:**

| Step 1 (`/admin/v1/user`) | Step 2 (`/api/v1/user`) | Meaning | Action |
|---------------------------|------------------------|---------|--------|
| 200 | (skipped) | Admin key | Use **adminapi** (`/admin/v1/`) |
| Not 200 | 200 | User key | Use **openapi** (`/api/v1/`) |
| 401 | 401 | Invalid key | Tell user to check `KB_CLOUD_ACCESS_KEY` / `KB_CLOUD_SECRET_KEY` |
| 404 or connection error | 404 or connection error | Wrong URL | Tell user to check `KB_CLOUD_BASE_URL` |

**Cache the result**: once determined, remember the key type for the rest of the session. Only re-probe if the user explicitly changes `KB_CLOUD_ACCESS_KEY` or `KB_CLOUD_BASE_URL`.

From this step, derive these variables for the rest of the session:

- `{prefix}` = `admin/v1` if admin key, or `api/v1` if user key
- `{api_doc}` = `adminapi` if admin key, or `openapi` if user key

### Step 1: Understand intent and identify operation

Analyze what the user wants and determine the resource + operation:

- "List clusters" → resource: cluster, operation: listCluster
- "Create a MySQL cluster" → resource: cluster, operation: createCluster
- "Show backups" → resource: backup, operation: listBackup
- "Delete cluster foo" → resource: cluster, operation: deleteCluster

If the user's intent is unclear, ask for clarification.

### Step 2: Navigate reference docs

Follow the **resource → operation → schema** chain under the references directory corresponding to the API determined in Step 0 (`references/adminapi/` or `references/openapi/`).

Let `{api_doc}` = `adminapi` or `openapi`, from Step 0.

**2a. Find the resource**

List the resources directory to see available resources, then read the one matching the user's intent:

```bash
ls references/{api_doc}/resources/
```

Pick the resource file that matches, then read it:

```
Read references/{api_doc}/resources/cluster.md
```

Resource files list all available operations for that resource (method + path + summary).

**2b. Read the operation file**

```
Read references/{api_doc}/operations/listCluster.md
```

Operation files contain:
- HTTP method and full path
- Path parameters, query parameters, header parameters
- Request body schema reference (for POST/PATCH)
- Response schema reference

**2c. Read schema files (as needed)**

When an operation has a request body, you **must** read the referenced schema to understand the body structure:

```
Read references/{api_doc}/schemas/clusterCreate/clusterCreate.md
```

Schema files list all fields, their types, and whether they are required. If a field's type links to another schema (e.g. `[clusterType](clusterType.md)`), follow the link and read that schema as needed.

When an operation references a response schema, read it as well to understand the return structure for better output formatting.

### Step 3: Build and execute the request

All requests use DigestAuth. Construct curl commands as follows:

**GET request (no body):**
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  -H "Content-Type: application/json" \
  "$KB_CLOUD_BASE_URL/{prefix}/organizations/{orgName}/clusters?clusterDefinition=mysql"
```

**POST/PATCH request (with body):**
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  -H "Content-Type: application/json" \
  -X POST \
  -d '{
    "name": "my-cluster",
    "engine": "mysql",
    "environmentName": "dev",
    "version": "8.0.30"
  }' \
  "$KB_CLOUD_BASE_URL/{prefix}/organizations/{orgName}/clusters"
```

**DELETE request:**
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  -X DELETE \
  "$KB_CLOUD_BASE_URL/{prefix}/organizations/{orgName}/clusters/{clusterName}"
```

**⚠️ Destructive operations require user confirmation:**

Non-GET operations (POST, PATCH, PUT, DELETE) modify or destroy resources. Before executing any of these, you **must**:

1. Show the user exactly what will happen (e.g. "This will **delete** cluster `prod-db` in org `my-org`. This action is irreversible.")
2. Show the full curl command that will be executed. Expand `$KB_CLOUD_BASE_URL` to show the real URL so the user can verify the target. **Keep `$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY` unexpanded** — never reveal the actual key and secret values.
3. Wait for explicit user confirmation before proceeding

Do NOT execute non-GET requests without confirmed user consent. GET requests may be executed directly.

**Key points:**
- Every request must include `--digest -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY"`
- POST/PATCH need `-H "Content-Type: application/json"` and `-d` with a JSON body
- Replace path parameters (e.g. `{orgName}`) with actual values
- Append query parameters to the URL

### Step 4: Present results

**Formatting JSON responses:**
- Prefer Python: `curl ... | python3 -m json.tool`
- Fall back to jq: `curl ... | jq`
- As a last resort, show the raw response

```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/{prefix}/organizations/{orgName}/clusters" \
  | python3 -m json.tool
```

**Presentation guidelines:**
- List operations: extract key fields (name, status, engine, version) and present as a table
- Single resource: show all important fields
- Create/update: show the result with key information highlighted
- Failures: show the error message with actionable suggestions

**Error handling:**

| Status | Meaning | Action |
|--------|---------|--------|
| 200 | Success | Display normally |
| 201 | Created | Show the new resource |
| 400 | Bad request | Show error details, verify parameters |
| 401 | Unauthorized | API key authentication failed, prompt user to check |
| 403 | Forbidden | Authenticated but lacks business permission for this operation |
| 404 | Not found | Verify resource name / org name |
| 409 | Conflict | Resource name already exists |
| 5xx | Server error | Retry later |

## Common patterns

### Path parameter substitution

Operation files contain paths with `{param}` placeholders:

- `{orgName}`: organization name
- `{clusterName}`: cluster name
- `{instanceName}`: instance name
- `{clusterID}`: cluster ID (UUID format)

**Never guess or fabricate parameter values.** When a required parameter is unknown, follow this priority:

1. **Look it up first** — use the API to find valid values. For example:
   - Need `{orgName}`? → list organizations
   - Need `{clusterName}`? → list clusters
   - Need `{environmentName}`? → list environments
2. **If exactly one result** → use it and tell the user (e.g. "Using org `my-org`")
3. **If multiple results** → present them to the user and ask which one to use
4. **If lookup fails or returns empty** → ask the user to provide the value

The same applies to query parameters and JSON body fields for POST/PATCH requests. Always resolve values from real data or user input — never send a request with made-up values.

### Pagination

List endpoints typically support pagination:

- `limit`: items per page (default is usually 10 or 20)
- `offset`: pagination offset

If the user needs all data, fetch the first page, check `pageResult` for more, and continue fetching.

### JSON body construction

When constructing a POST/PATCH body:
1. Read the schema file to understand all fields
2. **Required fields** must be included
3. Fill optional fields based on user requirements
4. Nested object fields (`[type](type.md)` links) may require reading sub-schemas

## Examples

### Example: List clusters

User: "List my clusters"

Execution flow:
1. Step 0 → {prefix} = admin/v1, {api_doc} = adminapi
2. Read `references/{api_doc}/resources/cluster.md` → find `GET /{prefix}/organizations/{orgName}/clusters`
3. Read `references/{api_doc}/operations/listCluster.md` → understand parameters
4. Ask user for orgName (if not known)
5. Execute:
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/{prefix}/organizations/my-org/clusters" \
  | python3 -m json.tool
```
6. Extract name, status, engine from `items[]`, present as a table

### Example: Create a cluster

User: "Create a MySQL cluster for me"

Execution flow:
1. Steps 0 through 2b as above, find `POST /{prefix}/organizations/{orgName}/clusters`
2. Read operation file, note request body is required, schema reference is `clusterCreate`
3. Read `references/{api_doc}/schemas/clusterCreate/clusterCreate.md`
4. Required fields: name, engine, environmentName
5. Ask user to fill in values (if environmentName is unknown, suggest listing environments first)
6. Build body, execute POST request
7. Present the creation result
