# databaseParameterListItem

database parameter item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the parameter |
| `description` | string | Yes | The description of the parameter |
| `type` | [databaseParameterType](databaseParameterType.md) | Yes |  |
| `since` | string | No | Since which version the parameter is supported |
| `deprecated` | string | No | which version the parameter is deprecated |
| `section` | string | No | The section of the parameter |
| `default` | object | No | The value of the parameter, if parameter is not set in tpl, it's value equal to cue default value. |
| `needRestart` | boolean | Yes | Whether the parameter requires a restart to take effect |
| `immutable` | boolean | Yes | Whether the parameter is an immutable parameter, immutable parameters cannot be modified |
| `level` | [databaseParameterLevel](databaseParameterLevel.md) | Yes |  |
| `maximum` | string | No | The maximum value of the parameter |
| `minimum` | string | No | The minimum value of the parameter |
| `enum` | any[] | No | The value options of the parameter |
| `unit` | string | No | The unit of the parameter |
| `recoverable` | boolean | No | Whether the parameter can be recovered during backup restore |

