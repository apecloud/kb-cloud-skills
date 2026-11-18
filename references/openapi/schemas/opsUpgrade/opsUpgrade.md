# opsUpgrade

Upgrade a component or selected instance templates. For template upgrades, the server overrides version with the minimum resulting template version.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `version` | string | Yes |  |
| `instanceTemplates` | instanceTemplateUpgrade[] | No |  |
| `component` | string | Yes |  |
| `schedule` | [taskSchedule](taskSchedule.md) | No |  |

