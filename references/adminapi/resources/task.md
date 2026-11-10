# task

Task APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/taskTypes` | List task types | [View](../operations/listTaskTypes.md) |
| GET | `/admin/v1/tasks` | List task | [View](../operations/listTasks.md) |
| GET | `/admin/v1/tasks/{taskId}` | Get task detail | [View](../operations/getTask.md) |
| GET | `/admin/v1/tasks/{taskId}/events` | List operation events related to a task | [View](../operations/listTaskEvents.md) |
| PATCH | `/admin/v1/tasks/{taskId}/stop` | Stop a task | [View](../operations/stopTask.md) |
| PATCH | `/admin/v1/tasks/{taskId}/retry` | Retry a task | [View](../operations/retryTask.md) |
| POST | `/admin/v1/tasks/{taskId}/cancel` | Cancel a task | [View](../operations/cancelTask.md) |
| POST | `/admin/v1/tasks/{taskId}/abort` | Force abort a task | [View](../operations/abortTask.md) |
| GET | `/admin/v1/tasks/{taskId}/log` | Get task log | [View](../operations/getTaskLog.md) |
| GET | `/admin/v1/tasks/{taskId}/steps/{stepId}/log` | Get task step log | [View](../operations/getTaskStepLog.md) |
| GET | `/admin/v1/scheduled-tasks` | List scheduled tasks | [View](../operations/listScheduledTasks.md) |
| GET | `/admin/v1/scheduled-tasks/{scheduledTaskId}` | Get scheduled task | [View](../operations/getScheduledTask.md) |
