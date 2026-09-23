# GET /admin/v1/ai-agent/conversations

**Resource:** [AI Agent](../resources/AI-Agent.md)
**List AI diagnosis conversations**
**Operation ID:** `listAIAgentConversations`

Lists platform AI diagnosis conversations for the current admin user.
Admin global entry and admin cluster-detail entry share the same history.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No |  |
| `after` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversations |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentConversationList](../schemas/aiAgentConversationList/aiAgentConversationList.md)

