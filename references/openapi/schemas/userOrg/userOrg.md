# userOrg

UserOrg is the payload for user organization

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | [orgStatus](orgStatus.md) | Yes |  |
| `expiredAt` | string (date-time) | Yes |  |
| `purgeError` | string | No |  |
| `allowedActions` | string[] | Yes |  |
| `orgId` | string | Yes | The ID of the organization |
| `role` | string | Yes | The role of the user in the organization |
| `displayName` | string | No | The display name of the organization |
| `name` | string | Yes | The name of the organization |
| `description` | string | No | The description of the organization |

