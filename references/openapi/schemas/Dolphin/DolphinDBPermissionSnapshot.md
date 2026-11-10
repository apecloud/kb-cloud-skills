# DolphinDBPermissionSnapshot

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subjectType` | string | Yes | user or group |
| `name` | string | Yes |  |
| `direct` | DolphinDBPermissionState[] | Yes |  |
| `effective` | DolphinDBPermissionState[] | Yes |  |
| `effectiveKnown` | boolean | Yes | True for users: effective is read from native getUserAccess(finalAccess=true). Groups expose direct settings only. |
| `inherited` | DolphinDBGroupPermissions[] | Yes |  |

