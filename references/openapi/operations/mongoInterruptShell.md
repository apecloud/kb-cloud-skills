# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/interrupt

**Resource:** [dms](../resources/dms.md)
**interrupt current MongoDB mongosh session operation**
**Operation ID:** `mongoInterruptShell`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `sessionID` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[MongoShellInterruptResponse](../schemas/Mongo/MongoShellInterruptResponse.md)

