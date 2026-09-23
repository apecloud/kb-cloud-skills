# RedisKeySummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | No |  |
| `type` | string | No |  |
| `ttl` | integer (int64) | No | key TTL in seconds; -1 means no expiration and -2 means missing key |
| `memory` | integer (int64) | No | memory usage in bytes when available |
| `length` | integer (int64) | No |  |
| `encoding` | string | No |  |
| `slot` | integer (int64) | No |  |
| `nodeId` | string | No |  |
| `aclAccess` | string | No | datasource ACL access result for this key |

