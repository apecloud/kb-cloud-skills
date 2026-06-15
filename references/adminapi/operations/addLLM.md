# POST /admin/v1/llm

**Resource:** [llm](../resources/llm.md)
**add LLM**
**Operation ID:** `addLLM`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | orgName the LLM belongs to |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [llm](../schemas/llm/llm.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when object is created successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[llm](../schemas/llm/llm.md)

