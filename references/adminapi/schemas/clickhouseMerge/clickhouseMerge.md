# clickhouseMerge

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | Database name. |
| `table` | string | No | Table name. |
| `hostName` | string | No | ClickHouse server host running the merge. |
| `elapsedSeconds` | number (double) | No | Seconds elapsed since the merge started. |
| `progress` | number (double) | No | Merge progress (0-1). |
| `numParts` | integer (int64) | No | Number of source parts. |
| `resultPartName` | string | No | Resulting part name. |
| `partitionId` | string | No | Partition being merged. |
| `isMutation` | boolean | No | Whether this merge also applies a mutation. |
| `memoryUsageBytes` | integer (int64) | No | Memory usage in bytes. |
| `rowsRead` | integer (int64) | No | Rows read by the merge. |
| `rowsWritten` | integer (int64) | No | Rows written by the merge. |
| `totalSizeBytesCompressed` | integer (int64) | No | Compressed size of the source parts. |

