# GET /api/v1/organizations/{orgName}/ai-agent/status

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Get AI diagnosis agent status**
**Operation ID:** `getAIAgentStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | AI diagnosis agent runtime status |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[aiAgentRuntimeStatus](../schemas/aiAgentRuntimeStatus/aiAgentRuntimeStatus.md)

