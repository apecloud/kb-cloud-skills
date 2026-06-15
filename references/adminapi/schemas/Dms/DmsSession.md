# DmsSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | session ID |
| `user` | string | Yes | user name |
| `tenant` | string | No | tenant name |
| `host` | string | Yes | client host information |
| `db` | string | No | database name |
| `command` | string | No | current command |
| `time` | integer (int64) | No | session duration time |
| `state` | string | No | session state |
| `info` | string | No | additional session information |
| `ip` | string | No | server ip |
| `port` | integer (int64) | No | server port |
| `protected` | boolean | No | whether the session is protected and don't allow to be killed |

