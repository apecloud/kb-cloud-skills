# clickhouseTableSpace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | Database name. |
| `table` | string | No | Table name. |
| `engine` | string | No | Table engine. |
| `bytesOnDisk` | integer (int64) | No | Physical bytes_on_disk across all hosts and disks. |
| `dataCompressedBytes` | integer (int64) | No | Sum of data_compressed_bytes. |
| `dataUncompressedBytes` | integer (int64) | No | Sum of data_uncompressed_bytes. |
| `compressionRatio` | number (double) | No | data_compressed_bytes / data_uncompressed_bytes. |
| `rows` | integer (int64) | No | Sum of active part rows. |
| `activeParts` | integer (int64) | No | Active part count used for the Too many parts risk check. |
| `partitionCount` | integer (int64) | No | Distinct partitions across disks and hosts. |
| `hosts` | integer (int64) | No | Number of hosts that own active parts for this table. |
| `lastModifiedAt` | string | No | Latest part modification time in RFC3339 UTC. |
| `risk` | string | No | normal, warning (parts >= parts_to_delay_insert) or critical (parts >= parts_to_throw_insert). |
| `disks` | clickhouseDiskUsage[] | No | Per-disk and per-host breakdown. |

