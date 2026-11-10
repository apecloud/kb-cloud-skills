# clickhouseSessionList

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collectedAt` | string | Yes | Collection time in RFC3339 UTC. |
| `clusterMode` | string | No | Detected deployment mode (standalone or cluster). When clusterAllReplicas fails and the local node is used instead, this is reported as standalone. |
| `items` | clickhouseSession[] | Yes | Active queries collected from system.processes, ordered by the requested metric. |
| `sources` | clickhouseSource[] | Yes | Per-source collection status. In cluster mode one entry is returned per clusterAllReplicas expression. |

