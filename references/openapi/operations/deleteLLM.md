# DELETE /api/v1/organizations/{orgName}/llm/{id}

**Resource:** [llm](../resources/llm.md)
**Delete LLM**
**Operation ID:** `deleteLLM`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `id` | path | string | Yes | ID of the LLM |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when object is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

