# clickhouseSQLAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collectedAt` | string | Yes | Collection time in RFC3339 UTC. |
| `status` | string | Yes | available when system.query_log was collected, unavailable when query logging is disabled or the table is missing. |
| `unavailableReason` | string | No | Stable reason code when status is unavailable, for example query_log_unavailable. |
| `message` | string | No | Human-readable guidance when the analysis is unavailable. |
| `range` | [clickhouseSQLAnalysisRange](clickhouseSQLAnalysisRange.md) | No |  |
| `summary` | [clickhouseSQLSummary](clickhouseSQLSummary.md) | No |  |
| `slowestQueries` | clickhouseSlowQuery[] | Yes | Top initial queries ordered by query_duration_ms descending. Distributed child queries are excluded via is_initial_query = 1. |
| `patterns` | clickhouseQueryPattern[] | Yes | Query patterns grouped by normalized_query_hash and ordered by the requested metric. |
| `failures` | clickhouseFailedQuery[] | Yes | Failed queries (type = ExceptionWhileProcessing) ordered by event_time descending. |
| `sources` | clickhouseSource[] | Yes | Per-source collection status. |

