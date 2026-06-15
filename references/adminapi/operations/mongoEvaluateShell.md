# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/evaluate

**Resource:** [dms](../resources/dms.md)
**evaluate input in a MongoDB mongosh session**
**Operation ID:** `mongoEvaluateShell`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `sessionID` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoShellEvaluateRequest](../schemas/Mongo/MongoShellEvaluateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 504 | (reference) |

**Success Response Schema:**

[MongoShellEvaluateResponse](../schemas/Mongo/MongoShellEvaluateResponse.md)

