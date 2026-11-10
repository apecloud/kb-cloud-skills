# DmsPagination

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `offset` | integer (int64) | No | Zero-based offset of this showData page. |
| `limit` | integer (int64) | No |  |
| `hasMore` | boolean | No | Whether another showData page exists; determined by reading one extra row. |
| `nextOffset` | integer (int64) | No | Present only when hasMore is true. |
| `totalRows` | integer (int64) | No | Exact count returned only by countOnly requests (including zero). |
| `orderColumns` | string[] | No | Primary-key columns used for ordering; empty means ordering is not guaranteed. Pages are not a fixed snapshot. |
| `rows_count` | integer | No |  |
| `page` | integer | No |  |
| `pages_count` | integer | No |  |
| `per_page` | integer | No |  |

