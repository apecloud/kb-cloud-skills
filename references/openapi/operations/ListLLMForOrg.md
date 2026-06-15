# GET /api/v1/organizations/{orgName}/llm

**Resource:** [llm](../resources/llm.md)
**List available LLM for org**
**Operation ID:** `ListLLMForOrg`
⚠️ **Deprecated**

available

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | available llm list |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[llmList](../schemas/llmList/llmList.md)

