# mysqlIndexSpace

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | Yes |  |
| `table` | string | Yes |  |
| `name` | string | Yes |  |
| `sizeBytes` | integer (int64) | No | Estimated from mysql.innodb_index_stats pages multiplied by innodb_page_size. |
| `isUnique` | boolean | Yes |  |
| `isPrimary` | boolean | Yes |  |
| `cardinality` | integer (int64) | Yes |  |
| `scanCount` | integer (int64) | No | COUNT_READ from performance_schema; resets with server statistics. |
| `lastStatUpdate` | string | No |  |

