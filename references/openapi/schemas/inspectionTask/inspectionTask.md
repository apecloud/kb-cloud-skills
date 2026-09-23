# inspectionTask

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `creator` | string | No |  |
| `status` | string | No |  |
| `engine` | string | No |  |
| `orgName` | string | No |  |
| `clusterID` | string | No |  |
| `clusterName` | string | No |  |
| `envName` | string | No |  |
| `envID` | string | No |  |
| `nodeName` | string | No | Node name(s) for inspection. Multiple nodes can be specified as a comma-separated string (e.g. "node1,node2,node3"). |
| `isAuto` | boolean | No |  |
| `savedDays` | integer | No |  |
| `expiredAt` | string (date-time) | No | Expiration timestamp fixed when the inspection report is created from savedDays. |
| `score` | integer (int64) | No | Weighted health score from 0 to 100 over evaluable inspection items only. Unknown results and items with info importance are excluded from both the numerator and denominator. The field is omitted when no item is evaluable; a present value of 0 is a valid evaluated score. |
| `result` | string | No | Task health conclusion derived from evaluable item states and criticality-aware score caps. Valid conclusions are red, yellow, green, and unknown. Unknown means no item is evaluable. Unknown items remain visible in the item list but do not override a red, yellow, or green conclusion derived from evaluable items. |
| `latestRunAt` | string (date-time) | No | Last inspection execution timestamp used for freshness checks. |
| `expectedInterval` | string | No | Expected first-version inspection interval assumption, for example 1h. |
| `nextRunAt` | string (date-time) | No | Expected next inspection time derived from latestRunAt and expectedInterval. |
| `isStale` | boolean | No | True when the latest inspection is older than the expected interval. Stale or missing inspection data must not be displayed as healthy. |
| `items` | inspectionTaskItem[] | No |  |
| `createdAt` | string (date-time) | No |  |
| `updatedAt` | string (date-time) | No |  |
| `timeRangeStart` | string (date-time) | No |  |
| `timeRangeEnd` | string (date-time) | No |  |

