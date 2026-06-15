# GET /admin/v1/llm/{id}

**Resource:** [llm](../resources/llm.md)
**Get LLM by ID**
**Operation ID:** `getLLMByID`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID of the LLM |

## Responses

| Status | Description |
|--------|-------------|
| 200 | LLM by ID |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[llm](../schemas/llm/llm.md)

