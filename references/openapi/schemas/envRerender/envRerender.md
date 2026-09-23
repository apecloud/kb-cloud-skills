# envRerender

Rule telling whether the env of an existing component is re-rendered when the mode transitions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allEnv` | boolean | No | Re-render the whole env of the component. |
| `includeEnvs` | string[] | No | Re-render only these env vars, when allEnv is not set. |

