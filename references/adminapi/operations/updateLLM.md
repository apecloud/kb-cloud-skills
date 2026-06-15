# PATCH /admin/v1/llm/{id}

**Resource:** [llm](../resources/llm.md)
**Update LLM**
**Operation ID:** `updateLLM`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of the LLM |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [llm](../schemas/llm/llm.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned when object is updated successfully. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[llm](../schemas/llm/llm.md)

