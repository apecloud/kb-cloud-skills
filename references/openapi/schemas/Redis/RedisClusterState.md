# RedisClusterState

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ready` | boolean | No |  |
| `reason` | string | No | reason code when cluster data management is not ready, for example requires_redis_cluster_mirror |
| `networkMode` | string | No |  |
| `mirrorReady` | boolean | No |  |
| `nodes` | RedisClusterNode[] | No |  |

