# aiAgentConversation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conversationId` | string | Yes |  |
| `entryClusterName` | string | No |  |
| `title` | string | No |  |
| `status` | [aiAgentConversationStatus](aiAgentConversationStatus.md) | Yes |  |
| `runtimeStatus` | [aiAgentRuntimeStatusCode](aiAgentRuntimeStatusCode.md) | No |  |
| `model` | string | No |  |
| `createdAt` | string (date-time) | Yes |  |
| `updatedAt` | string (date-time) | Yes |  |
| `lastMessage` | [aiAgentMessage](aiAgentMessage.md) | No |  |

