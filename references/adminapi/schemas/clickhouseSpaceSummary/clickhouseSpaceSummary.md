# clickhouseSpaceSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databaseCount` | integer (int64) | No | Number of databases with active parts. |
| `tableCount` | integer (int64) | No | Number of tables with active parts. |
| `totalBytes` | integer (int64) | No | Physical bytes_on_disk across all hosts. |
| `dataCompressedBytes` | integer (int64) | No | Sum of data_compressed_bytes. |
| `dataUncompressedBytes` | integer (int64) | No | Sum of data_uncompressed_bytes. |
| `compressionRatio` | number (double) | No | data_compressed_bytes / data_uncompressed_bytes. Lower is better; zero when uncompressed size is unknown. |
| `totalRows` | integer (int64) | No | Sum of active part rows across all hosts. |
| `activeParts` | integer (int64) | No | Number of active parts across all hosts. |
| `partitionCount` | integer (int64) | No | Sum of per-table partition counts. Replicated partitions can be counted more than once. |
| `warningTables` | integer (int64) | No | Tables whose active part count reached parts_to_delay_insert. |
| `criticalTables` | integer (int64) | No | Tables whose active part count reached parts_to_throw_insert. |
| `partsToDelayInsert` | integer (int64) | No | Effective parts_to_delay_insert from system.merge_tree_settings (default 150). |
| `partsToThrowInsert` | integer (int64) | No | Effective parts_to_throw_insert from system.merge_tree_settings (default 300). |

