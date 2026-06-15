# nodeResourceStats

ResourceStats holds the requests, limits, and available stats for a resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpuStats` | [resourceStats](resourceStats.md) | Yes |  |
| `memoryStats` | [resourceStats](resourceStats.md) | Yes |  |
| `filesystemStats` | [resourceStats](resourceStats.md) | No |  |
| `name` | string | Yes | Name of the node. |
| `instanceCount` | integer (int32) | No | Number of database cluster instances (pods) running on this node. |

