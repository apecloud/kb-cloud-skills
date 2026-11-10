# clickhouseClusterHealthSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `replicaCount` | integer (int64) | No | Number of replicated table replicas collected. |
| `nodeCount` | integer (int64) | No | Number of nodes in system.clusters. |
| `clusterCount` | integer (int64) | No | Number of distinct cluster names. |
| `totalReplicas` | integer (int64) | No | Sum of total_replicas across replicated tables. |
| `activeReplicas` | integer (int64) | No | Sum of active_replicas across replicated tables. |
| `readonlyReplicas` | integer (int64) | No | Replicas currently in readonly mode. |
| `sessionExpiredReplicas` | integer (int64) | No | Replicas whose Keeper session expired. |
| `maxAbsoluteDelaySeconds` | number (double) | No | Maximum absolute_delay in seconds. |
| `totalQueueSize` | integer (int64) | No | Sum of replication queue sizes. |
| `warningReplicas` | integer (int64) | No | Replicas classified as warning. |
| `criticalReplicas` | integer (int64) | No | Replicas classified as critical. |
| `unhealthyNodes` | integer (int64) | No | Nodes with connection errors, slowdowns or a non-zero estimated recovery time. |

