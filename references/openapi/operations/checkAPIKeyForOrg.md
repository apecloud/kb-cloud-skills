# POST /api/v1/organizations/{orgName}/llm/check

**Resource:** [llm](../resources/llm.md)
**check apikey available for org**
**Operation ID:** `checkAPIKeyForOrg`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [checkAPIKey](../schemas/checkAPIKey/checkAPIKey.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | apikey available |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

