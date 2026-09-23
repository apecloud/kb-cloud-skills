# RedisDataContext

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `datasourceName` | string | No |  |
| `aclUser` | string | No | Redis ACL user name. Prefer acl.user for new clients. |
| `acl` | [RedisACLContext](RedisACLContext.md) | No |  |
| `dbIndex` | integer (int64) | No | Current logical Redis database index for this request context. |
| `dbCount` | integer (int64) | No | Available logical Redis database count. Non-cluster Redis defaults to 16 when the server does not expose a count; Redis Cluster is always 1. |
| `mode` | string | No | Redis architecture mode, such as standalone, replication, sentinel, or cluster |
| `readOnly` | boolean | No |  |
| `capabilities` | [RedisDataCapabilities](RedisDataCapabilities.md) | No |  |
| `cluster` | [RedisClusterState](RedisClusterState.md) | No |  |

