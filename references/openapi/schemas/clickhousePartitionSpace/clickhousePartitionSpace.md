# clickhousePartitionSpace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | Database name. |
| `table` | string | No | Table name. |
| `partitionId` | string | No | partition_id from system.parts. |
| `partition` | string | No | Human-readable partition expression. |
| `rows` | integer (int64) | No | Sum of rows across hosts. |
| `bytesOnDisk` | integer (int64) | No | Physical bytes_on_disk across hosts. |
| `dataCompressedBytes` | integer (int64) | No | Sum of data_compressed_bytes. |
| `dataUncompressedBytes` | integer (int64) | No | Sum of data_uncompressed_bytes. |
| `activeParts` | integer (int64) | No | Active part count across hosts. |
| `hosts` | integer (int64) | No | Number of hosts that own this partition. |
| `minDate` | string | No | Minimum min_date in the partition. |
| `maxDate` | string | No | Maximum max_date in the partition. |

