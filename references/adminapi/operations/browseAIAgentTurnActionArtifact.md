# GET /admin/v1/organizations/{orgName}/ai-agent/conversations/{conversationId}/turn-actions/{actionId}/artifacts/{artifactId}/browse

**Resource:** [AI Agent](../resources/AI-Agent.md)
**Browse a generated AI diagnosis report artifact**
**Operation ID:** `browseAIAgentTurnActionArtifact`

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
| 200 | Generated report artifact content for browser preview |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |
| 503 | (reference) |

