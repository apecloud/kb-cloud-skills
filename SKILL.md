---
name: kb-cloud-skills
description: Execute real operations against the KubeBlocks Cloud API. Use this skill when users need to query, create, modify, or delete KubeBlocks Cloud resources.
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

**One key works for only one API.**

## Environment variables

Before any operation, verify these environment variables are set:

| Variable | Description |
|----------|-------------|
| `KB_CLOUD_BASE_URL` | API base URL, e.g. `https://cloudapi.apecloud.cn` |
| `KB_CLOUD_ACCESS_KEY` | API accessKey (get it from **Personal Settings → API Keys**) |
| `KB_CLOUD_SECRET_KEY` | API secretKey (get it from **Personal Settings → API Keys**) |

If any are missing, prompt the user to set them:
```bash
export KB_CLOUD_BASE_URL="https://cloudapi.apecloud.cn"
export KB_CLOUD_ACCESS_KEY="YOUR_ACCESS_KEY"
export KB_CLOUD_SECRET_KEY="YOUR_SECRET_KEY"
```

## Agent workflow

Follow these steps for every user request:

### Step 0: Probe key ownership (once per session)

One key belongs to only one API. Probe with `GET /user`, trying openapi first, then adminapi.

**Cache the result**: once the probe succeeds, remember which API the key belongs to (openapi or adminapi) for the rest of the session. Do NOT re-probe on every request. Only re-probe if the user explicitly changes `KB_CLOUD_ACCESS_KEY` or `KB_CLOUD_BASE_URL`.

**Important**: use `-i` to get the full HTTP response (headers + body). Judge by the HTTP status code; the response body content is irrelevant for this step.

```bash
# Try openapi
curl -s -i --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/api/v1/user"

# Try adminapi
curl -s -i --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/admin/v1/user"
```

**Decision table:**

| Result | Meaning | Action |
|--------|---------|--------|
| openapi returns 2xx | Key is for openapi | Remember this, use openapi (`/api/v1/`) |
| adminapi returns 2xx | Key is for adminapi | Remember this, use adminapi (`/admin/v1/`) |
| Both return 401/403 | Key is invalid | Tell user to check `KB_CLOUD_ACCESS_KEY` and `KB_CLOUD_SECRET_KEY` |
| Both return 404 or other | Wrong URL | Tell user to check `KB_CLOUD_BASE_URL` |

### Step 1: Understand intent and identify operation

Analyze what the user wants and determine the resource + operation:

- "List clusters" → resource: cluster, operation: listCluster
- "Create a MySQL cluster" → resource: cluster, operation: createCluster
- "Show backups" → resource: backup, operation: listBackup
- "Delete cluster foo" → resource: cluster, operation: deleteCluster

If the user's intent is unclear, ask for clarification.

### Step 2: Navigate reference docs

Follow the **resource → operation → schema** chain under `references/openapi/` or `references/adminapi/` (whichever was determined in Step 0).

**2a. Find the resource**

List the resources directory to see available resources, then read the one matching the user's intent:

```bash
ls references/openapi/resources/
```

Pick the resource file that matches, then read it:

```
Read references/openapi/resources/cluster.md
```

Resource files list all available operations for that resource (method + path + summary).

**2b. Read the operation file**

```
Read references/openapi/operations/listCluster.md
```

Operation files contain:
- HTTP method and full path
- Path parameters, query parameters, header parameters
- Request body schema reference (for POST/PATCH)
- Response schema reference

**2c. Read schema files (as needed)**

When an operation has a request body, you **must** read the referenced schema to understand the body structure:

```
Read references/openapi/schemas/clusterCreate/clusterCreate.md
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
  "$KB_CLOUD_BASE_URL/api/v1/organizations/{orgName}/clusters?clusterDefinition=mysql"
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
  "$KB_CLOUD_BASE_URL/api/v1/organizations/{orgName}/clusters"
```

**DELETE request:**
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  -X DELETE \
  "$KB_CLOUD_BASE_URL/api/v1/organizations/{orgName}/clusters/{clusterName}"
```

**⚠️ Destructive operations require user confirmation:**

Non-GET operations (POST, PATCH, PUT, DELETE) modify or destroy resources. Before executing any of these, you **must**:

1. Show the user exactly what will happen (e.g. "This will **delete** cluster `prod-db` in org `my-org`. This action is irreversible.")
2. Show the full curl command that will be executed. **Keep the environment variables unexpanded** (`$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY`) — never reveal the actual key and secret values.
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
  "$KB_CLOUD_BASE_URL/api/v1/organizations/{orgName}/clusters" \
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
| 401 | Unauthorized | Key is invalid, prompt user to check |
| 403 | Forbidden | Key lacks permission for this operation |
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
1. Probe openapi → 2xx, use openapi
2. Read `references/openapi/resources/cluster.md` → find `GET /api/v1/organizations/{orgName}/clusters`
3. Read `references/openapi/operations/listCluster.md` → understand parameters
4. Ask user for orgName (if not known)
5. Execute:
```bash
curl -s --digest \
  -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" \
  "$KB_CLOUD_BASE_URL/api/v1/organizations/my-org/clusters" \
  | python3 -m json.tool
```
6. Extract name, status, engine from `items[]`, present as a table

### Example: Create a cluster

User: "Create a MySQL cluster for me"

Execution flow:
1. Steps 0 through 2b as above, find `POST /api/v1/organizations/{orgName}/clusters`
2. Read operation file, note request body is required, schema reference is `clusterCreate`
3. Read `references/openapi/schemas/clusterCreate/clusterCreate.md`
4. Required fields: name, engine, environmentName
5. Ask user to fill in values (if environmentName is unknown, suggest listing environments first)
6. Build body, execute POST request
7. Present the creation result
