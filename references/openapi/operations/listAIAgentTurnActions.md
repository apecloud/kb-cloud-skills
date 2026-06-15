# GET /api/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions

**Resource:** [AI Agent](../resources/AI-Agent.md)
**List stable AI diagnosis turn process actions**
**Operation ID:** `listAIAgentTurnActions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `turnId` | query | string | No |  |
| `after` | query | string | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Stable AI diagnosis process actions |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentTurnActionList](../schemas/aiAgentTurnActionList/aiAgentTurnActionList.md)

