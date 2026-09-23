# RedisKeyMutateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes |  |
| `expectedType` | string | No |  |
| `operation` | string | Yes | Redis key mutation operation, such as set, hset, hdel, lset, lpush, rpush, sadd, srem, zadd, zrem, xadd, xtrim, json_set, json_del, expire, persist, rename, or delete |
| `payload` | object | No |  |
| `confirm` | boolean | No |  |

