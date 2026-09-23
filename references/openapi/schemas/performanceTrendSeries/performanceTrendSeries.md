# performanceTrendSeries

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metric` | string | Yes |  |
| `displayName` | [localizedDescription](localizedDescription.md) | Yes |  |
| `category` | string | Yes | Metric category. Values include availability, performance, connections, resource, capacity, innodb, and vacuumWraparound. |
| `dimension` | string | No | Optional series dimension. Values include cluster, instance, pvc, and database. |
| `labels` | object | No | Optional dimension labels, for example instance, pvc, role, or datname. |
| `unit` | string | Yes |  |
| `warnThreshold` | number (double) | No | Optional warning threshold in the same unit as this metric. |
| `critThreshold` | number (double) | No | Optional critical threshold in the same unit as this metric. |
| `thresholdDirection` | string | No | Optional threshold direction. Values are above, below, or boolean. |
| `points` | performanceTrendPoint[] | Yes |  |

