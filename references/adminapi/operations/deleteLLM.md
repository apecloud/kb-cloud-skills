# DELETE /admin/v1/llm/{id}

**Resource:** [llm](../resources/llm.md)
**Delete LLM**
**Operation ID:** `deleteLLM`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of the LLM |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when object is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

