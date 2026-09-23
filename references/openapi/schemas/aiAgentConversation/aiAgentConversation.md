# aiAgentConversation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conversationId` | string | Yes |  |
| `entryClusterName` | string | No |  |
| `agentMode` | [aiAgentMode](aiAgentMode.md) | No |  |
| `agent_profile` | [aiAgentProfile](aiAgentProfile.md) | No |  |
| `contextState` | [aiAgentContextState](aiAgentContextState.md) | No |  |
| `scopeLabel` | string | No | Safe display label for the conversation scope. It does not expose profile paths, skills paths, credentials, or endpoints. |
| `title` | string | No |  |
| `status` | [aiAgentConversationStatus](aiAgentConversationStatus.md) | Yes |  |
| `runtimeStatus` | [aiAgentRuntimeStatusCode](aiAgentRuntimeStatusCode.md) | No |  |
| `model` | string | No |  |
| `createdAt` | string (date-time) | Yes |  |
| `updatedAt` | string (date-time) | Yes |  |
| `lastMessage` | [aiAgentMessage](aiAgentMessage.md) | No |  |

