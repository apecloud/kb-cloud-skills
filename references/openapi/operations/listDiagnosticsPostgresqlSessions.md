# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/postgresql/sessions

**Resource:** [diagnostics](../resources/diagnostics.md)
**List PostgreSQL session basic diagnostics**
**Operation ID:** `listDiagnosticsPostgresqlSessions`

List PostgreSQL session basic diagnostics records. The response includes waitEventType and waitEvent so clients can identify lock-waiting sessions without loading lock rows.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `limit` | query | integer (int64) | No | Maximum number of sessions to return. When omitted, the API returns the complete point-in-time session snapshot. When provided, the value must be positive. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[postgresqlSessionList](../schemas/postgresqlSessionList/postgresqlSessionList.md)

