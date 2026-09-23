# mysqlSQLAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `source` | string | Yes | Data source. M1 uses performance_schema.events_statements_summary_by_digest. |
| `status` | string | Yes | Source status. Expected values are available or unavailable. |
| `unavailableReason` | string | No | Reason when status is unavailable, such as performance_schema_disabled, digest_consumer_disabled, permission_denied, or query_failed. |
| `message` | string | No | User-facing recovery guidance when SQL analysis is unavailable. |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. It is not a sampling-window end time. |
| `firstSeen` | string | No | Earliest FIRST_SEEN timestamp across currently visible digest rows, when available. |
| `lastSeen` | string | No | Latest LAST_SEEN timestamp across currently visible digest rows, when available. |
| `limit` | integer (int64) | Yes | Effective row limit after backend normalization. |
| `orderBy` | string | Yes | Effective sort key. Expected values are totalTime, meanTime, maxTime, or calls. |
| `totalTimeMsAll` | number (double) | No | Total execution time in milliseconds across all visible digest rows, not limited to the returned top-N items. |
| `callsAll` | integer (int64) | No | Total execution count across all visible digest rows, not limited to the returned top-N items. |
| `digestLost` | integer (int64) | No | Number of statement digests not recorded because the digest table was full, when exposed by the server. |
| `items` | mysqlSQLFingerprint[] | Yes | SQL fingerprint ranking rows from Performance Schema. The list may be empty when no statement statistics exist. |

