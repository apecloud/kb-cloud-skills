# GET /api/v1/organizations/{orgName}/llm/{id}

**Resource:** [llm](../resources/llm.md)
**Get LLM by ID in org**
**Operation ID:** `getLLMByIDInOrg`
⚠️ **Deprecated**

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `id` | path | string | Yes | ID of the LLM |

## Responses

| Status | Description |
|--------|-------------|
| 201 | LLM by ID |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[llm](../schemas/llm/llm.md)

