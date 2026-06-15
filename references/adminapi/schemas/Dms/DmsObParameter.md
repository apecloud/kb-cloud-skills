# DmsObParameter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the parameter |
| `value` | string | Yes | The value of the parameter |
| `dataType` | string | No | The type of the parameter value |
| `description` | string | Yes | The description of the parameter |
| `enum` | any[] | No | The value options of the parameter |
| `maximum` | string | No | The maximum value of the parameter |
| `minimum` | string | No | The minimum value of the parameter |
| `immutable` | boolean | No | Whether the parameter is an immutable parameter, immutable parameters cannot be modified |
| `isVariable` | boolean | No | Whether the parameter is variable or a parameter |
| `editLevel` | string | No | EditLevel represents the way the configuration item is modified. |
| `readOnly` | boolean | No | Whether the parameter is read-only |

