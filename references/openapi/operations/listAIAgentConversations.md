# GET /api/v1/organizations/{orgName}/ai-agent/conversations

**Resource:** [AI Agent](../resources/AI-Agent.md)
**List AI diagnosis conversations**
**Operation ID:** `listAIAgentConversations`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `limit` | query | integer | No |  |
| `after` | query | string | No |  |
| `clusterName` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversations |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentConversationList](../schemas/aiAgentConversationList/aiAgentConversationList.md)

