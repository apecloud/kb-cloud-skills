# parameterTemplateDiffItem

A parameter or raw file difference in a parameter template

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fileName` | string | Yes | The name of the configuration file |
| `parameterName` | string | No | The name of the changed parameter. Empty when rawContent is true and the whole file differs. |
| `oldValue` | string | No | The value from the matching default template |
| `newValue` | string | No | The value from the custom parameter template |

