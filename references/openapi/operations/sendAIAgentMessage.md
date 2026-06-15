# POST /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/messages

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Send a user message and start or continue AI diagnosis**
**Operation ID:** `sendAIAgentMessage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [aiAgentSendMessageRequest](../schemas/aiAgentSendMessageRequest/aiAgentSendMessageRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis message accepted |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[aiAgentSendMessageResponse](../schemas/aiAgentSendMessageResponse/aiAgentSendMessageResponse.md)

