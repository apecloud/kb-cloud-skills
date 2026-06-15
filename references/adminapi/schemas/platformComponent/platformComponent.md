# platformComponent

Platform component summary with monitoring and log query metadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Component name |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `status` | [platformComponentStatus](platformComponentStatus.md) | Yes |  |
| `version` | string | No | Component version |
| `replicas` | integer (int64) | No | Number of ready replicas |
| `dashboardUID` | string | No | Grafana dashboard UID for this component |
| `logJobName` | string | No | Log query job name for this component |

