# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/prompt

**Resource:** [dms](../resources/dms.md)
**get MongoDB mongosh session prompt**
**Operation ID:** `mongoGetShellPrompt`

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

[MongoShellPromptResponse](../schemas/Mongo/MongoShellPromptResponse.md)

