# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/clickhouse/spaceAnalysis

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get ClickHouse space analysis**
**Operation ID:** `getDiagnosticsClickhouseSpaceAnalysis`

Analyze system.parts, system.merges and system.mutations across the cluster. Returns table and partition level disk usage, compression efficiency, per-disk and per-host distribution, part explosion risk (parts_to_delay_insert / parts_to_throw_insert), running merges and unfinished mutations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `database` | query | string | No | Filter by database. Omit or empty = all databases. |
| `tableLimit` | query | integer (int64) | No | Maximum number of top tables. Defaults to 20 and is capped at 200. |
| `partitionLimit` | query | integer (int64) | No | Maximum number of top partitions. Defaults to 20 and is capped at 200. |
| `mergeLimit` | query | integer (int64) | No | Maximum number of merges and unfinished mutations. Defaults to 20 and is capped at 200. |

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

[clickhouseSpaceAnalysis](../schemas/clickhouseSpaceAnalysis/clickhouseSpaceAnalysis.md)

