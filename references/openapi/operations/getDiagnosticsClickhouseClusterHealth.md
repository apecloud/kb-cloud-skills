# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/clickhouse/clusterHealth

**Resource:** [diagnostics](../resources/diagnostics.md)
**Get ClickHouse replica and cluster health**
**Operation ID:** `getDiagnosticsClickhouseClusterHealth`

Analyze system.replicas and system.clusters. Returns replication delay, Keeper queue backlog, readonly/session-expired replicas and shard/replica topology with per-node connection errors. Replica rows are collected through clusterAllReplicas, while the topology is read from the connected node's system.clusters view.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

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

[clickhouseClusterHealth](../schemas/clickhouseClusterHealth/clickhouseClusterHealth.md)

