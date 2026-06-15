# parameterOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type |
| `referenceEngine` | [parameterOptionRef](parameterOptionRef.md) | No |  |
| `exportTpl` | boolean | No | If set to true, the current parameters of the component can be exported and saved as a parameter template. |
| `enableTemplate` | boolean | No | If set to true, the parameter templates of the component can be used. Mainly used by frontend. |
| `enableRawContent` | boolean | No | If set to true, the component can display the raw content of the parameter configuration file. |
| `configSpecs` | configSpecOption[] | No | all parameter configuration specs of this component |
| `disableHA` | boolean | No |  |
| `templates` | parameterTemplate[] | No | parameter templates, including default parameter templates for different major versions or default parameter templates for different purposes. |
| `initOptions` | [initOption](initOption.md) | No |  |

