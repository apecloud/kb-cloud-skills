# GET /admin/v1/scheduled-tasks

**Resource:** [task](../resources/task.md)
**List scheduled tasks**
**Operation ID:** `listScheduledTasks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `provider` | query | string | No | Filter by scheduler provider |
| `status` | query | scheduledTaskStatus | No | Filter by scheduled task status |
| `pageNumber` | query | integer (int64) | No | Page number, starting from 1 |
| `pageSize` | query | integer (int64) | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scheduled task list |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |
| 501 | (reference) |

**Success Response Schema:**

[scheduledTaskList](../schemas/scheduledTaskList/scheduledTaskList.md)

