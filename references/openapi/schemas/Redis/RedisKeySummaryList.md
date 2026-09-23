# RedisKeySummaryList

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `items` | RedisKeySummary[] | No |  |
| `nextCursor` | string | No | Cursor for the next SCAN page. Empty or "0" means the scan is complete. |
| `hasMore` | boolean | No | Whether another key page should be requested. |
| `progress` | [RedisKeyScanProgress](RedisKeyScanProgress.md) | No |  |

