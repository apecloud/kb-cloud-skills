# postgresqlSQLAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `source` | string | Yes | Data source. M1 uses pg_stat_statements only. |
| `status` | string | Yes | Source status. Expected values are available or unavailable. |
| `unavailableReason` | string | No | Reason when status is unavailable, such as extension_disabled, permission_denied, or query_failed. |
| `statsReset` | string | No | UTC timestamp reported by pg_stat_statements_info.stats_reset when available. Empty means the source did not expose this timestamp. |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. It is not a sampling-window end time. |
| `limit` | integer (int64) | Yes | Effective row limit after backend normalization. |
| `orderBy` | string | Yes | Effective sort key. Expected values are totalTime, meanTime, maxTime, or calls. |
| `totalTimeMsAll` | number (double) | No | Total execution time in milliseconds across all visible pg_stat_statements rows, not limited to the returned top-N items. Present only when the source is available. |
| `callsAll` | integer (int64) | No | Total execution count across all visible pg_stat_statements rows, not limited to the returned top-N items. Present only when the source is available. |
| `items` | postgresqlSQLFingerprint[] | Yes | SQL fingerprint ranking rows from pg_stat_statements. The list may be empty when no statement statistics exist. |

