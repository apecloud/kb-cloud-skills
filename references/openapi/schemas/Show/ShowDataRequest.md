# ShowDataRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | the database of the table or view |
| `table` | string | No | the target table or view name |
| `limit` | integer | No | Rows per batch, from 1 to 2000; defaults to 200. |
| `offset` | integer (int64) | No | Zero-based offset. Include 0 for the first paged request; omit for legacy data plus total-count behavior. Paged requests do not count the table. |
| `countOnly` | boolean | No | Only return pagination.totalRows, without loading data. |

