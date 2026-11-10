# clickhouseClusterHealth

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collectedAt` | string | Yes | Collection time in RFC3339 UTC. |
| `status` | string | Yes | Collection status. success when every source was collected, partial when topology or replicas could only be partially read. |
| `overallStatus` | string | No | Derived health status. normal, warning or critical. |
| `clusterMode` | string | No | Detected deployment mode (standalone or cluster). |
| `summary` | [clickhouseClusterHealthSummary](clickhouseClusterHealthSummary.md) | No |  |
| `replicas` | clickhouseReplicaHealth[] | Yes | Replicated tables ordered by risk, absolute delay and queue size. |
| `nodes` | clickhouseClusterNode[] | Yes | Shard and replica topology from system.clusters on the connected node. |
| `sources` | clickhouseSource[] | Yes | Per-source collection status. |

