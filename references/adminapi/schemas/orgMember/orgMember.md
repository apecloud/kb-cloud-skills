# orgMember

Org Member info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `displayName` | string | No | The display name of User. Read-Only |
| `email` | string | No | The email of the user. Sourced from the user profile; may be empty
if the user has not set one. Cannot be changed via the org-member
API (use the user-profile API instead).
 |
| `role` | string | Yes | The role of the User in the Org. |
| `userId` | string | Yes | The ID of User. Read-Only |
| `freezed` | boolean | No | Return true if the member is freezed in the organization |

