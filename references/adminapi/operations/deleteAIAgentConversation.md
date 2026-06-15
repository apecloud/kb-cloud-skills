# DELETE /admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Delete an AI diagnosis conversation**
**Operation ID:** `deleteAIAgentConversation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversation deleted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentDeleteConversationResponse](../schemas/aiAgentDeleteConversationResponse/aiAgentDeleteConversationResponse.md)

