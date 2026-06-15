# POST /admin/v1/llm/check

**Resource:** [llm](../resources/llm.md)
**check apikey available**
**Operation ID:** `checkAPIKey`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [llm](../schemas/llm/llm.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | apikey available |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[checkAPIKey](../schemas/checkAPIKey/checkAPIKey.md)

