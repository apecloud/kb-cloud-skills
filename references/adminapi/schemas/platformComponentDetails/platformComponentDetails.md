# platformComponentDetails

Platform component detail including pods and observability metadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Component name |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `status` | [platformComponentStatus](platformComponentStatus.md) | Yes |  |
| `version` | string | No |  |
| `replicas` | integer (int64) | No |  |
| `dashboardUID` | string | No | Grafana dashboard UID for this component |
| `logJobName` | string | No | Log query job name for this component |
| `pods` | platformComponentPod[] | No | List of pods for this component |

