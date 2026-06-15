# aiConversation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string (uuid) | No | Conversation ID |
| `userId` | string | No | User ID associated with the conversation |
| `clusterName` | string | No | Name of the cluster associated with the conversation |
| `orgName` | string | No | Name of the organization associated with the conversation |
| `title` | string | No | Optional title for the conversation |
| `type` | string | No | Type of the conversation, can be chatbi or chatops. |
| `createdAt` | string (date-time) | No | Timestamp of when the conversation was created |
| `updatedAt` | string (date-time) | No | Timestamp of when the conversation was last updated |

