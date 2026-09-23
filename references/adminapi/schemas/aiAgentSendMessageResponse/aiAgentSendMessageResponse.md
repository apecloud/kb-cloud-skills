# aiAgentSendMessageResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `messageId` | string | Yes |  |
| `turnId` | string | Yes |  |
| `status` | [aiAgentTurnStatus](aiAgentTurnStatus.md) | Yes |  |
| `eventsUrl` | string | No |  |
| `agentMode` | [aiAgentMode](aiAgentMode.md) | No |  |
| `agent_profile` | [aiAgentProfile](aiAgentProfile.md) | No |  |
| `contextState` | [aiAgentContextState](aiAgentContextState.md) | No |  |
| `scopeLabel` | string | No | Safe display label for the run scope. It does not expose profile paths, skills paths, credentials, or endpoints. |

