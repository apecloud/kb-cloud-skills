# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/clickhouse/sessions/{queryId}

**Resource:** [diagnostics](../resources/diagnostics.md)
**Kill a ClickHouse query**
**Operation ID:** `killDiagnosticsClickhouseQuery`

Terminate a running query by query_id. In cluster mode KILL QUERY ON CLUSTER is used so the initial query and its remote sub-queries are terminated together; otherwise KILL QUERY runs on the connected node.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `queryId` | path | string | Yes | ClickHouse query_id to terminate. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Query killed successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

