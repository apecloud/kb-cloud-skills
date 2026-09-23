# aggregateTaskResultSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `error` | integer | No |  |
| `warning` | integer | No |  |
| `normal` | integer | No |  |
| `unknown` | integer | No | Number of completed tasks with no evaluable inspection item. Tasks that contain both evaluable and unknown items retain the conclusion derived from their evaluable items. |

