# containerInfo

Container information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Container name |
| `image` | string | No | Container image |
| `ready` | boolean | No | Container ready status |
| `restartCount` | integer | No | Container restart count |
| `livenessProbe` | object | No | Liveness probe configuration |
| `readinessProbe` | object | No | Readiness probe configuration |
| `resources` | object | No | Container resource usage |

