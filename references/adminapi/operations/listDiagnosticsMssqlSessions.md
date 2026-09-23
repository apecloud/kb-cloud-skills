# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions

**Resource:** [diagnostics](../resources/diagnostics.md)
**List SQL Server sessions**
**Operation ID:** `listDiagnosticsMssqlSessions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `limit` | query | integer (int64) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[mssqlSessionSnapshot](../schemas/mssqlSessionSnapshot/mssqlSessionSnapshot.md)

