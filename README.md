# kb-cloud-skills

An AI agent skill for executing real operations against the [KubeBlocks Cloud](https://kblocks.com) API. Gives any AI agent the ability to query, create, modify, and delete KubeBlocks Cloud resources using natural language.

## What it does

This project bundles the full KubeBlocks Cloud API reference (user-facing `/api/v1/` and admin `/admin/v1/`) into a structured, on-demand-loadable format. An AI agent reads `SKILL.md` as its entry point, which teaches it how to:

1. Auto-detect which API your key belongs to
2. Navigate the reference docs to find the right endpoint
3. Build authenticated HTTP requests (DigestAuth)
4. Execute API calls and present results

## Prerequisites

- An AI agent that supports the [SKILL.md](https://claude.com/claude-code) format
- A KubeBlocks Cloud API key (accessKey + secretKey)
- Node.js ≥ 18 (only needed to regenerate reference docs from OpenAPI specs)

## Setup

Set the following environment variables:

```bash
export KB_CLOUD_BASE_URL="https://cloudapi.apecloud.cn"
export KB_CLOUD_ACCESS_KEY="YOUR_ACCESS_KEY"
export KB_CLOUD_SECRET_KEY="YOUR_SECRET_KEY"
```

| Variable | Description | Example |
|----------|-------------|---------|
| `KB_CLOUD_BASE_URL` | API base URL | `https://cloudapi.apecloud.cn` |
| `KB_CLOUD_ACCESS_KEY` | API accessKey | `AKIDxxxx` |
| `KB_CLOUD_SECRET_KEY` | API secretKey | `xxxxxxxxxxxxxxxx` |

> One key works for only one API (`/api/v1/` or `/admin/v1/`). The skill auto-detects which one on first use.

## Usage

Once the skill is loaded, interact with the agent in natural language:

| Prompt | Result |
|--------|--------|
| "List my clusters" | `GET /api/v1/organizations/{org}/clusters` |
| "Create a MySQL 8.0 cluster named prod-db in dev" | `POST /api/v1/organizations/{org}/clusters` |
| "Show backups for prod-db" | `GET /api/v1/organizations/{org}/clusters/prod-db/backups` |
| "What environments are available?" | `GET /admin/v1/environments` |
| "Delete cluster staging-kafka" | `DELETE /api/v1/organizations/{org}/clusters/staging-kafka` |
| "List all engines" | `GET /admin/v1/engines` |

### With Claude Code

Register as a project-level skill in `.claude/settings.json`:

```json
{
  "skills": {
    "kb-cloud-skills": "https://github.com/apecloud/kb-cloud-skills"
  }
}
```

Or clone and use locally:

```bash
git clone https://github.com/apecloud/kb-cloud-skills /path/to/kb-cloud-skills
claude --project /path/to/kb-cloud-skills
```

### With other agents

Any agent that reads `SKILL.md` as a knowledge base can use this project. Point the agent to this repository or a local clone — it will follow the instructions in `SKILL.md` to navigate the reference docs and make API calls.

## Supported resources

#### User-facing API (`/api/v1/`)

cluster, backup, restore, account, kafka, redis, rdbms, mongodb, postgresql, dameng, oceanbase, mssql, hive, opsrequest, clusterLog, parameter, parameterTemplate, tls, ipWhitelist, inspection, alert, alertRule, alertConfig, alertObject, alertInhibit, alertReceiver, alertStrategy, clusterAlertSwitch, database, benchmark, import, dataReplication, disasterRecovery, blueGreenDeployment, engine, class, classTypes, storage, storageClass, loadBalancer, vipPool, backupRepo, backupMethod, recycleBinCluster, dms, billing, metering, SLA, member, session, event, task, feature, relation, pricing, llm, AI-Agent, AI, project, environment, engineOption...

#### Admin API (`/admin/v1/`)

environment, engine, organization, user, role, administrator, cluster, engineLicense, engineOption, imageRegistry, storageClass, resourceStats, monitorDataSink, provider, platformParameter, platformComponent, SLA, pricing, license, billing, metering, metrics, vuln, serviceVersion, enableServiceVersion, progress...

> Full resource list with operation counts is in `references/openapi/resources/` and `references/adminapi/resources/`.

## Authentication

Uses **DigestAuth** (RFC 7616). Every API call follows this pattern:

```bash
curl -s --digest -u "$KB_CLOUD_ACCESS_KEY:$KB_CLOUD_SECRET_KEY" "$KB_CLOUD_BASE_URL/api/v1/..."
```

`accessKey` is the username, `secretKey` is the password.

## Troubleshooting

| Symptom | Likely cause | Solution |
|---------|-------------|----------|
| Both APIs return 401/403 | Invalid or expired key | Check `KB_CLOUD_ACCESS_KEY` and `KB_CLOUD_SECRET_KEY` |
| Both APIs return 404 | Wrong base URL | Check `KB_CLOUD_BASE_URL` |
| Missing parameters | Operation requires inputs | Provide org name, cluster name, etc. when prompted |
| 403 on a specific operation | Key lacks permission | Ask your admin to grant the required role |

## Project structure

```
.
├── SKILL.md              # Agent entry point — teaches the agent how to work
├── README.md
├── package.json          # Build scripts
├── src/
│   ├── openapi.yaml      # Source OpenAPI spec — user-facing API
│   └── adminapi.yaml     # Source OpenAPI spec — admin API
└── references/
    ├── openapi/           # Generated reference docs for /api/v1/
    │   ├── resources/     # 77 resource index files
    │   ├── operations/    # 720 operation detail files
    │   └── schemas/       # 572 schema groups, 690 schema files
    └── adminapi/          # Generated reference docs for /admin/v1/
        ├── resources/     # 88 resource index files
        ├── operations/    # 851 operation detail files
        └── schemas/       # 669 schema groups, 790 schema files
```

## Update reference docs

When the upstream API specs change:

```bash
yarn bundle:build      # Bundle the upstream OpenAPI specs
yarn skills:build      # Regenerate reference docs
```
