# mysqlSpaceSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databaseName` | string | Yes |  |
| `databaseSizeBytes` | integer (int64) | Yes |  |
| `dataBytes` | integer (int64) | Yes |  |
| `indexBytes` | integer (int64) | Yes |  |
| `freeBytes` | integer (int64) | Yes | DATA_FREE reported by information_schema. Its per-table meaning is most reliable with innodb_file_per_table. |
| `tableCount` | integer (int64) | Yes |  |
| `tableListTruncated` | boolean | Yes |  |
| `indexListTruncated` | boolean | Yes |  |
| `indexSizeSource` | string | No |  |

