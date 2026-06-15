# user

Admin user info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID for the user |
| `userName` | string | Yes | The name of the user, is unique |
| `displayName` | string | No | The display name of the user |
| `email` | string | No | The email for the user |
| `phoneNumber` | [phoneNumber](phoneNumber.md) | No |  |
| `createdAt` | string (date-time) | Yes |  |
| `updatedAt` | string (date-time) | Yes |  |
| `isDefaultPassword` | boolean | No | return true if the default admin user need to reset password |
| `description` | string | No | The description for the user |

