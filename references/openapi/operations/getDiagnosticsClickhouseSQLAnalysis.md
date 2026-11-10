# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/clickhouse/sqlAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get ClickHouse SQL analysis**
**Operation ID:** `getDiagnosticsClickhouseSQLAnalysis`

Analyze system.query_log for the selected range. Only initial queries (is_initial_query = 1) are counted so distributed child queries are not double counted. Returns the slowest queries by query_duration_ms, query patterns grouped by normalized_query_hash, and failed queries (ExceptionWhileProcessing) with exception_code. When log_queries is disabled or system.query_log is missing, the endpoint returns status=unavailable together with guidance instead of failing.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `range` | query | string | No | Time range based on query_log event_time. Defaults to 24h. Allowed values: 1h, 6h, 24h, 7d. |
| `limit` | query | integer (int64) | No | Maximum number of entries per list. Defaults to 20 and is capped at 200. |
| `orderBy` | query | string | No | Pattern ordering metric. Defaults to totalDuration. Allowed values: totalDuration, meanDuration, maxDuration, calls, memory, readRows, failures. |
| `database` | query | string | No | Filter by current_database. Omit or empty = all databases. |
| `user` | query | string | No | Filter by ClickHouse user. Omit or empty = all users. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[clickhouseSQLAnalysis](../schemas/clickhouseSQLAnalysis/clickhouseSQLAnalysis.md)

