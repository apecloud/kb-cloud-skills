# aiAgentCreateConversationRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | string | No |  |
| `model` | string | No |  |
| `entryClusterName` | string | No |  |
| `contexts` | aiAgentScope[] | No | Optional creation-time context. When entryClusterName is omitted, the
first clusterName here binds the conversation to cluster diagnosis.
 |

