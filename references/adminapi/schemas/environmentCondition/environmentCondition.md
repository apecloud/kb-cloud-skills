# environmentCondition

EnvironmentCondition contains details for the current condition of this environment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | Human-readable message indicating details about last transition. |
| `reason` | string | No | Unique, one-word, CamelCase reason for the condition's last transition. |
| `status` | [environmentConditionStatus](environmentConditionStatus.md) | Yes |  |
| `type` | string | Yes | Type is the type of the condition. |

