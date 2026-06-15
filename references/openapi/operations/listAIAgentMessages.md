# GET /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/messages

**Resource:** [AI Agent](../resources/AI-Agent.md)
**List AI diagnosis conversation messages**
**Operation ID:** `listAIAgentMessages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `after` | query | string | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis messages |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentMessageList](../schemas/aiAgentMessageList/aiAgentMessageList.md)

