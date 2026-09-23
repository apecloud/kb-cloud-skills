# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions/{pid}

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get PostgreSQL session basic diagnostics**
**Operation ID:** `getDiagnosticsPostgresqlSession`

Get one PostgreSQL session basic diagnostics record by backend pid.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `pid` | path | integer (int64) | Yes | PostgreSQL backend process id. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[postgresqlSession](../schemas/postgresqlSession/postgresqlSession.md)

