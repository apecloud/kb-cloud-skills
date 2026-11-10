# DolphinDBPermissionState

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `privilege` | string | Yes | Native snapshot field. ACCESS_READ/INSERT/UPDATE/DELETE represent global table/database access. |
| `globalEffect` | string | No | allow, deny or none; absent when not applicable. |
| `allowedObjects` | string[] | No |  |
| `deniedObjects` | string[] | No |  |
| `value` | number (double) | No | Native quota or account limit, including default sentinel values. |

