# RedisKeyScanProgress

Redis key browser scan progress for the current page.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | string | No | Scan scope, either node or cluster. |
| `total` | integer (int64) | No | Total keys in the scan scope when available. |
| `scanned` | integer (int64) | No | Number of key names returned by SCAN in this page before type filtering. |
| `loaded` | integer (int64) | No | Number of key summaries loaded in this page after filtering and metadata lookup. |
| `complete` | boolean | No | Whether the scan cursor is complete after this page. |

