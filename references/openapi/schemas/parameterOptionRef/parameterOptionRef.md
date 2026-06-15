# parameterOptionRef

Reference another engine's parameter option to reuse its parameter configuration.
If parameterOptionRef is set, the referenced engine's parameter option (identified by
engineName + component) is used as the only source of parameter configuration. Fields explicitly set in
the local parameterOption will be ignored.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `engineName` | string | Yes | The engine name to reference parameter configuration from. |
| `component` | string | Yes | The component type in the referenced engine whose parameter option to inherit. |

