# POST /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/stop

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Stop the current AI diagnosis turn**
**Operation ID:** `stopAIAgentConversation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversation stopped |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentStopConversationResponse](../schemas/aiAgentStopConversationResponse/aiAgentStopConversationResponse.md)

