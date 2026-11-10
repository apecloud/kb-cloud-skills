# scheduledTaskSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scheduledTaskId` | string | Yes | ID of the scheduled task |
| `name` | string | Yes | Stable name of the scheduled task |
| `provider` | [scheduledTaskProvider](scheduledTaskProvider.md) | No |  |
| `cronExpression` | string | No | Cron expression used to schedule the task |
| `lastExecutionStatus` | [scheduledTaskLastExecutionStatus](scheduledTaskLastExecutionStatus.md) | No |  |
| `enabled` | [scheduledTaskEnableStatus](scheduledTaskEnableStatus.md) | No |  |
| `scope` | string | No | Scope affected by the task, such as platform, organization, environment, or cluster |
| `status` | [scheduledTaskStatus](scheduledTaskStatus.md) | Yes |  |
| `lastRunAt` | string | No | Most recent execution start time as a Unix timestamp in seconds |
| `nextRunAt` | string | No | Next scheduled execution time as a Unix timestamp in seconds |
| `createdAt` | string (date-time) | Yes | Creation time of the scheduled task record |

