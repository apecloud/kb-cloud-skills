# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/sessions/{pid}

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Kingbase session diagnostics**
**Operation ID:** `getDiagnosticsKingbaseSession`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `pid` | path | integer (int64) | Yes |  |

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

[kingbaseSessionDetail](../schemas/kingbaseSessionDetail/kingbaseSessionDetail.md)

