# account

Cluster account information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `privilegesList` | [privilegeList](privilegeList.md) | No |  |
| `component` | string | No | Specify the name of component to be connected. If not specified, pick the first one. |
| `instance` | string | No | Specify the name of instance to be connected. |
| `name` | string | Yes | Specify the name of user, which must be unique. |
| `password` | string | No | Specify the password of user. The default value is empty, which means a random password will be generated. |
| `role` | [accountRoleType](accountRoleType.md) | Yes |  |
| `extra` | object | No | extra information of account |

