# task

Task APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/taskTypes` | List task types | [View](../operations/listTaskTypes.md) |
| GET | `/admin/v1/tasks` | List task | [View](../operations/listTasks.md) |
| GET | `/admin/v1/tasks/{taskId}` | Get task detail | [View](../operations/getTask.md) |
| PATCH | `/admin/v1/tasks/{taskId}/stop` | Stop a task | [View](../operations/stopTask.md) |
| PATCH | `/admin/v1/tasks/{taskId}/retry` | Retry a task | [View](../operations/retryTask.md) |
| POST | `/admin/v1/tasks/{taskId}/cancel` | Cancel a task | [View](../operations/cancelTask.md) |
| GET | `/admin/v1/tasks/{taskId}/log` | Get task log | [View](../operations/getTaskLog.md) |
| GET | `/admin/v1/tasks/{taskId}/steps/{stepId}/log` | Get task step log | [View](../operations/getTaskStepLog.md) |
