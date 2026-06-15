# taskListItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | Yes | ID of the scaling task |
| `taskName` | string | Yes | Name of the task |
| `taskType` | string | Yes | Type of task operation |
| `subTaskType` | string | No | Subtype of task operation. |
| `status` | [taskStatus](taskStatus.md) | Yes |  |
| `resourceType` | string | No | Resource type of the task |
| `resourceId` | string | No | Resource ID of the task |
| `resourceName` | string | No | Resource name of the task |
| `orgName` | string | No | Organization name of the task |
| `createdAt` | string (date-time) | Yes | Timestamp when the task was created |
| `updatedAt` | string (date-time) | Yes | Timestamp when the task was last updated |
| `startedAt` | string (date-time) | No | Timestamp when the task was deleted |
| `completionTime` | string (date-time) | No | Time when the task completed or failed |
| `message` | string | No | Detailed message about the task status |
| `progress` | integer | No | Progress percentage of the task |
| `operator` | string | No | The user created the task |
| `scheduled` | [taskSchedule](taskSchedule.md) | No |  |

