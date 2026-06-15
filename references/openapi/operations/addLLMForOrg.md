# POST /api/v1/organizations/{orgName}/llm

**Resource:** [llm](../resources/llm.md)
**add LLM for org**
**Operation ID:** `addLLMForOrg`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [llm](../schemas/llm/llm.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | llm added successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

