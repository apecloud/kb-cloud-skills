# GET /admin/v1/tasks/{taskId}

**Resource:** [task](../resources/task.md)
**Get task detail**
**Operation ID:** `getTask`

Get task

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | ID of the task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Current status of the task |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[task](../schemas/task/task.md)

