# PATCH /admin/v1/tasks/{taskId}/retry

**Resource:** [task](../resources/task.md)
**Retry a task**
**Operation ID:** `retryTask`

retry task

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | ID of the task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Current status of the task |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[task](../schemas/task/task.md)

