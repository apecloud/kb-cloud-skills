# task

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | Yes | ID of the scaling task |
| `taskName` | string | Yes | Name of the task |
| `taskType` | string | Yes | Type of task operation |
| `subTaskType` | string | No | Subtype of task operation |
| `status` | [taskStatus](taskStatus.md) | Yes |  |
| `createdAt` | string (date-time) | Yes | Timestamp when the task was created |
| `updatedAt` | string (date-time) | Yes | Timestamp when the task was last updated |
| `deletedAt` | string (date-time) | No | Timestamp when the task was deleted |
| `startedAt` | string (date-time) | No | Timestamp when the task was deleted |
| `completionTime` | string (date-time) | No | Time when the task completed or failed |
| `message` | string | No | Detailed message about the task status |
| `progress` | integer | No | Progress percentage of the task |
| `steps` | taskStep[] | No |  |
| `parallelism` | integer | No | Degree of parallelism for the task |
| `failurePolicy` | [taskFailurePolicy](taskFailurePolicy.md) | No |  |
| `retryLimit` | integer | No | Maximum number of retries for the task |
| `timeoutSecond` | integer | No | Timeout duration for the task in seconds |
| `operator` | string | No | The user created the task |
| `resourceType` | string | No | Resource type of the task, e.g. "cluster", "environment", etc. |
| `resourceId` | string | No | Resource ID of the task |
| `resourceName` | string | No | Resource name of the task |
| `orgName` | string | No | Organization name of the task |
| `scheduled` | [taskSchedule](taskSchedule.md) | No |  |

