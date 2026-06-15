# aiAgentMessage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `messageId` | string | Yes |  |
| `conversationId` | string | Yes |  |
| `turnId` | string | No |  |
| `role` | [aiAgentMessageRole](aiAgentMessageRole.md) | Yes |  |
| `contexts` | aiAgentScope[] | No |  |
| `parts` | aiAgentMessagePart[] | Yes |  |
| `createdAt` | string (date-time) | Yes |  |

