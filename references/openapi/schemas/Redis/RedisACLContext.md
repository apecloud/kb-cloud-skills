# RedisACLContext

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user` | string | No | Redis ACL user bound to the datasource. |
| `keyPatterns` | string[] | No | Key patterns the datasource ACL user is allowed to access. |
| `channelPatterns` | string[] | No | Pub/Sub channel patterns the datasource ACL user is allowed to access. |
| `commandRules` | string[] | No | Command allow/deny rules for the datasource ACL user. |

