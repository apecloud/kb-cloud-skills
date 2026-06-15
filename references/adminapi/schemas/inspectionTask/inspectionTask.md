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
| `score` | integer | No |  |
| `result` | string | No |  |
| `items` | inspectionTaskItem[] | No |  |
| `createdAt` | string (date-time) | No |  |
| `updatedAt` | string (date-time) | No |  |
| `timeRangeStart` | string (date-time) | No |  |
| `timeRangeEnd` | string (date-time) | No |  |

