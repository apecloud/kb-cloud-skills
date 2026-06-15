# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/shell/sessions/{sessionID}/completions

**Resource:** [dms](../resources/dms.md)
**get completions for a MongoDB mongosh session**
**Operation ID:** `mongoCompleteShell`

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

**Schema:** [MongoShellCompletionsRequest](../schemas/Mongo/MongoShellCompletionsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[MongoShellCompletionsResponse](../schemas/Mongo/MongoShellCompletionsResponse.md)

