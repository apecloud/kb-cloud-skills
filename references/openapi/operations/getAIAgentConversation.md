# GET /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Get an AI diagnosis conversation**
**Operation ID:** `getAIAgentConversation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentConversation](../schemas/aiAgentConversation/aiAgentConversation.md)

