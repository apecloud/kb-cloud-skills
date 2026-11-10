# clickhouseMutation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | Database name. |
| `table` | string | No | Table name. |
| `hostName` | string | No | ClickHouse server host running the mutation. |
| `mutationId` | string | No | Mutation identifier. |
| `command` | string | No | Mutation command (ALTER/UPDATE/DELETE) with string and numeric literals and comments masked as ?. |
| `createTime` | string | No | Mutation creation time in RFC3339 UTC. |
| `partsToDo` | integer (int64) | No | Parts still waiting to be mutated. |
| `latestFailedPart` | string | No | Most recent part that failed mutation. |
| `latestFailTime` | string | No | Most recent mutation failure time in RFC3339 UTC. |
| `latestFailReason` | string | No | Most recent mutation failure reason. |

