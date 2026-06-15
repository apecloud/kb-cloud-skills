# accountListItem

Cluster account information.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | No | Component type. |
| `name` | string | Yes | The name of user. |
| `password` | string | No | The password of user. |
| `role` | [accountListRoleType](accountListRoleType.md) | No |  |
| `privilegesList` | [privilegeList](privilegeList.md) | No |  |
| `extra` | object | No | extra information of account |

