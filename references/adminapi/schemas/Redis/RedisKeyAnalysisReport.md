# RedisKeyAnalysisReport

One Redis keys analysis report row. Rows are persisted per shard. The query
response appends one non-persisted aggregate row with isSummary=true.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | No |  |
| `clusterId` | string | No |  |
| `shardName` | string | No |  |
| `isSummary` | boolean | No | True for the aggregate row that is not persisted. |
| `createTime` | string (date-time) | No |  |
| `parameters` | object | No | Parameters for a Redis keys analysis task. topBigKey and topSlot are capped at 500.
numOfElemMin filters keys whose element count is below the threshold. bigKeySizeMin
filters keys whose memory usage is below the threshold (for example "10kb").
 |
| `typeStat` | object | No | Key statistics by Redis data type: {type: {count, bytes}}. |
| `byteLevelStat` | object | No | Key statistics by memory size bucket: {bucket: {count, bytes}}. |
| `totalNumKeys` | integer (int64) | No | Sum of counts across all byteLevelStat buckets. |
| `totalSizeKeys` | integer (int64) | No | Sum of bytes across all byteLevelStat buckets. |
| `expireStat` | object | No | Key statistics by remaining TTL bucket: {bucket: {count, bytes}}. |
| `topBigKeyByteStat` | RedisKeyEntry[] | No |  |
| `topBigKeyElemStat` | RedisKeyEntry[] | No |  |
| `topSlotKeyByteStat` | object[] | No | Top cluster slots by memory usage: [{slot: bytes}]. Only populated for Redis Cluster mode. |
| `topSlotKeyCountStat` | object[] | No | Top cluster slots by key count: [{slot: count}]. Only populated for Redis Cluster mode. |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topBigKey` | integer (int64) | No |  |
| `numOfElemMin` | integer (int64) | No |  |
| `bigKeySizeMin` | string | No |  |
| `topSlot` | integer (int64) | No |  |

