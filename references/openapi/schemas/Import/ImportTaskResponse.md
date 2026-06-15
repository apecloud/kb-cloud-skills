# ImportTaskResponse

Import task response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Import task ID |
| `name` | string | Yes | Import name |
| `status` | [ImportTaskStatus](ImportTaskStatus.md) | Yes |  |
| `sourceEndpoint` | string | Yes | Source endpoint address |
| `targetClusterName` | string | Yes | Target cluster name |
| `progress` | integer (int32) | Yes | Overall progress |
| `sourceType` | string | Yes | Data source type |
| `targetEngine` | string | Yes | Target engine type |
| `syncTimestamp` | string (date-time) | No | Sync timestamp |
| `delaySecond` | integer | No | Delay seconds |
| `createdAt` | string (date-time) | Yes | Creation time |
| `updatedAt` | string (date-time) | Yes | Update time |
| `finishedAt` | string (date-time) | No | Finish time |
| `message` | string | Yes | Operation result message |

