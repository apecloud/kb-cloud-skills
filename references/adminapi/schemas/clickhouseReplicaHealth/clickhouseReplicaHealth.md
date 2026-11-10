# clickhouseReplicaHealth

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | Database name. |
| `table` | string | No | Table name. |
| `hostName` | string | No | ClickHouse server host that reported this replica. |
| `isReadonly` | boolean | No | Replica is in readonly mode. Usually indicates Keeper or network problems. |
| `isSessionExpired` | boolean | No | Keeper session expired. |
| `absoluteDelaySeconds` | number (double) | No | absolute_delay from system.replicas. |
| `queueSize` | integer (int64) | No | replication queue size. |
| `insertsInQueue` | integer (int64) | No | Number of inserts waiting in the replication queue. |
| `mergesInQueue` | integer (int64) | No | Number of merges waiting in the replication queue. |
| `futureParts` | integer (int64) | No | Number of future parts. |
| `partsToCheck` | integer (int64) | No | Number of parts to check. |
| `totalReplicas` | integer (int64) | No | total_replicas for the table. |
| `activeReplicas` | integer (int64) | No | active_replicas for the table. |
| `logMaxIndex` | integer (int64) | No | Maximum log index in Keeper. |
| `logPointer` | integer (int64) | No | Last applied log index. |
| `lastQueueUpdate` | string | No | Last replication queue update time in RFC3339 UTC. |
| `zookeeperPath` | string | No | Keeper path of the table. |
| `replicaName` | string | No | Replica name. |
| `replicaPath` | string | No | Replica path in Keeper. |
| `zookeeperException` | string | No | Last Keeper exception, empty when healthy. |
| `lastQueueUpdateException` | string | No | Last replication queue update exception, empty when healthy. |
| `risk` | string | No | normal, warning or critical. |
| `issues` | string[] | No | Detected issue codes such as readonly, session_expired, replication_delay, queue_backlog, missing_replicas, keeper_error or queue_update_error. |

