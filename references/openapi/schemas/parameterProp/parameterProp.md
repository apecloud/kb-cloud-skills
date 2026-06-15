# parameterProp

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the parameter |
| `description` | string | No | The description of the parameter |
| `type` | string | Yes | The type of the parameter value |
| `value` | object | No | The value of the parameter, if parameter is not set in tpl, it's value equal to cue default value. |
| `default` | object | No | The value of the parameter, if parameter is not set in tpl, it's value equal to cue default value. |
| `needRestart` | boolean | Yes | Whether the parameter requires a restart to take effect |
| `immutable` | boolean | Yes | Whether the parameter is an immutable parameter, immutable parameters cannot be modified |
| `maximum` | string | No | The maximum value of the parameter |
| `minimum` | string | No | The minimum value of the parameter |
| `enum` | any[] | No | The value options of the parameter |

