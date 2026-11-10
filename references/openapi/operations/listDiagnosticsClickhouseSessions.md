# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/clickhouse/sessions

**Resource:** [diagnostics](../resources/diagnostics.md)
**List active ClickHouse queries**
**Operation ID:** `listDiagnosticsClickhouseSessions`

List active queries from system.processes across every shard and replica via clusterAllReplicas. Returns elapsed time, current and peak memory usage, read/write progress and the server host for each query so long-running or memory-heavy queries can be located quickly. The diagnostics query itself is excluded from the result.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `limit` | query | integer (int64) | No | Maximum number of queries to return. Defaults to 100 and is capped at 1000. |
| `orderBy` | query | string | No | Sort metric. Defaults to elapsed. Allowed values: elapsed, memoryUsage, memoryUsageRatio, peakMemoryUsage, readRows, readBytes. |
| `database` | query | string | No | Filter by current database. Omit or empty = all databases. |

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

[clickhouseSessionList](../schemas/clickhouseSessionList/clickhouseSessionList.md)

