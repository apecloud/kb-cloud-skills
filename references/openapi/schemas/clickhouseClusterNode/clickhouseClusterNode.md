# clickhouseClusterNode

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cluster` | string | No | Cluster name. |
| `shardNum` | integer (int64) | No | Shard number. |
| `shardWeight` | integer (int64) | No | Shard weight. |
| `replicaNum` | integer (int64) | No | Replica number inside the shard. |
| `hostName` | string | No | Configured host name. |
| `hostAddress` | string | No | Configured host address. |
| `port` | integer (int64) | No | Configured TCP port. |
| `isLocal` | boolean | No | Whether this node is the connected node. |
| `user` | string | No | Configured user. |
| `defaultDatabase` | string | No | Configured default database. |
| `errorsCount` | integer (int64) | No | Connection errors observed for this node. |
| `slowdownsCount` | integer (int64) | No | Slowdown events observed for this node. |
| `estimatedRecoveryTime` | integer (int64) | No | Estimated recovery time in seconds, zero when the node is healthy. |
| `risk` | string | No | normal or warning. |
| `issues` | string[] | No | Detected issue codes such as connection_errors, slowdowns or estimated_recovery_time. |

