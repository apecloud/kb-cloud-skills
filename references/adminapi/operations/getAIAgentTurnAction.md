# GET /admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Get one stable AI diagnosis turn process action**
**Operation ID:** `getAIAgentTurnAction`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `actionId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis process action detail |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentTurnAction](../schemas/aiAgentTurnAction/aiAgentTurnAction.md)

