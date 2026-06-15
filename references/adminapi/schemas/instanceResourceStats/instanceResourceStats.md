# instanceResourceStats

InstanceResourceStats holds the requests, limits, and available stats for an instance.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpuStats` | [resourceStats](resourceStats.md) | Yes |  |
| `memoryStats` | [resourceStats](resourceStats.md) | Yes |  |
| `ephemeralStorageStats` | [resourceStats](resourceStats.md) | No |  |
| `name` | string | Yes | Name of the instance. |
| `type` | [instanceResourceStatsType](instanceResourceStatsType.md) | No |  |
| `engine` | string | No | Engine type of the instance. |
| `engineVersion` | string | No | Engine version of the instance. |
| `role` | string | No | Role of the instance. |
| `clusterName` | string | No | Name of the cluster this instance belongs to. |
| `orgName` | string | No | Name of the organization this instance's cluster belongs to. |
| `clusterStatus` | string | No | Cluster status. |

