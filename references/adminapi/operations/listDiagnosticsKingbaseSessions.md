# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/sessions

**Resource:** [diagnostics](../resources/diagnostics.md)
**List Kingbase session diagnostics**
**Operation ID:** `listDiagnosticsKingbaseSessions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `limit` | query | integer (int64) | No | Maximum number of sessions to return. Defaults to 200. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[kingbaseSessionList](../schemas/kingbaseSessionList/kingbaseSessionList.md)

