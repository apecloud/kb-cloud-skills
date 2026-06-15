# chatRequest

Chat message request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `orgName` | string | Yes | Organization name |
| `clusterName` | string | Yes | Cluster name |
| `sessionId` | string | Yes | Session ID |
| `messageID` | string | No | Message ID |
| `query` | string | Yes | Query content |
| `model` | string | Yes | LLM model |
| `datasourceName` | string | No | Datasource name |
| `database` | string | No | Database involved in the chat |
| `schema` | string | No | Schema involved in the chat |
| `tables` | string[] | No | Tables involved in the chat |

