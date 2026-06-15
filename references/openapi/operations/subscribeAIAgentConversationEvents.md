# GET /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/events

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Subscribe to AI diagnosis conversation events**
**Operation ID:** `subscribeAIAgentConversationEvents`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `after` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis event stream |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

