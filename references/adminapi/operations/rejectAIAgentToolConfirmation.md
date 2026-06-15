# POST /admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/tool-confirmations/{confirmationId}/reject

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Reject one AI diagnosis tool confirmation**
**Operation ID:** `rejectAIAgentToolConfirmation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `confirmationId` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [aiAgentToolConfirmationDecisionRequest](../schemas/aiAgentToolConfirmationDecisionRequest/aiAgentToolConfirmationDecisionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Tool confirmation rejected |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentToolConfirmationDecisionResponse](../schemas/aiAgentToolConfirmationDecisionResponse/aiAgentToolConfirmationDecisionResponse.md)

