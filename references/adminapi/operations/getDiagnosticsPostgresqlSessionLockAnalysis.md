# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions/{pid}/lockAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get PostgreSQL session lock analysis**
**Operation ID:** `getDiagnosticsPostgresqlSessionLockAnalysis`

Get read-only lock analysis for one PostgreSQL backend pid from the current DMS PostgreSQL lock snapshot.

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

[postgresqlLockAnalysis](../schemas/postgresqlLockAnalysis/postgresqlLockAnalysis.md)

