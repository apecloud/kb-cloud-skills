# ACLUser

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `role` | [accountListRoleType](accountListRoleType.md) | Yes |  |
| `privileges` | [redisPrivilegeType](redisPrivilegeType.md) | No |  |
| `name` | string | Yes | ACL user name |
| `enabled` | boolean | No | Whether the user is enabled |
| `nopass` | boolean | No | Whether the user requires no password |
| `passwords` | string[] | No | List of plain text passwords |
| `password_hashes` | string[] | No | List of hashed passwords |
| `passwords_to_remove` | string[] | No | List of passwords to be removed |
| `password_hashes_to_remove` | string[] | No | List of password hashes to be removed |
| `acl_rules` | string | No | Custom ACL rules |

