# aiMessage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string (uuid) | No | Message ID |
| `conversationId` | string (uuid) | No | ID of the conversation this message belongs to |
| `senderType` | [senderType](senderType.md) | No |  |
| `content` | string | No | Content of the message |
| `isFavorited` | boolean | No | Whether the message is favorited by user |
| `metadata` | [metadataObject](metadataObject.md) | No |  |
| `createdAt` | string (date-time) | No | Timestamp of when the message was created |
| `updatedAt` | string (date-time) | No | Timestamp of when the message was last updated |

