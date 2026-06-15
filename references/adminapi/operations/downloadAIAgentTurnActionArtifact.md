# GET /admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}/artifacts/{artifactId}/download

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Download a generated AI diagnosis report artifact**
**Operation ID:** `downloadAIAgentTurnActionArtifact`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `conversationId` | path | string | Yes |  |
| `actionId` | path | string | Yes |  |
| `artifactId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generated report artifact content |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 503 | (reference) |

