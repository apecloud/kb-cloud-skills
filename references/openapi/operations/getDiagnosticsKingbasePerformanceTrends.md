# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/kingbase/performanceTrends

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get Kingbase performance trends**
**Operation ID:** `getDiagnosticsKingbasePerformanceTrends`

Get read-only Kingbase performance trends from backend-owned metrics. The response covers resource, connection, workload, database, capacity, and availability series and does not expose PromQL, internal endpoints, or credentials.
V9 queries.perSecond requires track_sql=on and track_sql_item either empty (all items) or containing the complete sqltime item. Each QPS sample must have matching settings from the same scrape target and timestamp; disabled, missing, stale, or conflicting settings exclude that sample from both series and summaries. V8 QPS does not depend on these V9 settings. Unknown or unverified major versions (including V10) omit QPS without querying it.
An absent QPS series means collection availability cannot be confirmed; it does not mean zero load or prove that SQL tracking is disabled. Check the database version, SQL tracking settings, and collection of same-scrape settings metrics. Source success describes queries with displayable results, not the availability of every metric. Empty metrics do not produce query-failure warnings.
xid.age, database.sizeBytes, and locks.observedSessionCount cover user databases only, excluding esrep, kingbase, security, template0, template1, and empty or placeholder (-) database names. xid.age is not an instance-wide wraparound safety check: system database ages are not shown. Its 150M/180M warning/critical thresholds are static references, not the cluster's freeze settings or database limits.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `range` | query | string | No | Controlled query range. Allowed values are 1h, 6h, 24h, and 7d. Defaults to 1h. |
| `step` | query | string | No | Controlled query granularity. Allowed values are 1m, 5m, 15m, and 1h. For range 7d, step must be at least 5m; the default is 1h. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[performanceTrends](../schemas/performanceTrends/performanceTrends.md)

