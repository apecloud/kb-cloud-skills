# instanceTemplateEnv

One fillable env var on an instance template, for frontend rendering.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Env var name written to the instance template. |
| `label` | [localizedDescription](localizedDescription.md) | No |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `required` | boolean | No | If true, the frontend should treat this env as required. Create does not re-check. |
| `default` | string | No | Default value shown by the frontend. |

