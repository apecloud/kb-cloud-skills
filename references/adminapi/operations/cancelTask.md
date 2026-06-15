# POST /admin/v1/tasks/{taskId}/cancel

**Resource:** [task](../resources/task.md)
**Cancel a task**
**Operation ID:** `cancelTask`

Cancel a task by taskID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | ID of the task |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Task cancelled successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

