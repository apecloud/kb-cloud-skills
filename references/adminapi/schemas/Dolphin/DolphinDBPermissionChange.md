# DolphinDBPermissionChange

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes | grant, deny or revoke. Revoke clears the direct setting; it does not deny inherited access. |
| `privilege` | string | Yes | Native privilege name from capabilities. |
| `objects` | string[] | No |  |
| `value` | number (double) | No | Numeric quota value; only for grant of quota privileges. |

