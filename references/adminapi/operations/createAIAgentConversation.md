# POST /admin/v1/organizations/{orgName}/ai-agent/conversations

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Create an AI diagnosis conversation**
**Operation ID:** `createAIAgentConversation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [aiAgentCreateConversationRequest](../schemas/aiAgentCreateConversationRequest/aiAgentCreateConversationRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis conversation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentConversation](../schemas/aiAgentConversation/aiAgentConversation.md)

