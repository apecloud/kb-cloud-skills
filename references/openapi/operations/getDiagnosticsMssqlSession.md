# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/mssql/sessions/{sessionId}

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get a SQL Server session**
**Operation ID:** `getDiagnosticsMssqlSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `sessionId` | path | integer (int64) | Yes |  |
| `startedAt` | query | string | Yes |  |

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

[mssqlSession](../schemas/mssqlSession/mssqlSession.md)

