# GET /admin/v1/tasks/{taskId}/steps/{stepId}/log

**Resource:** [task](../resources/task.md)
**Get task step log**
**Operation ID:** `getTaskStepLog`

Get logs for a specific task step (supports job type steps)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | ID of the task |
| `stepId` | path | string | Yes | ID of the step |
| `follow` | query | boolean | No | Follow log stream (streaming mode for running steps) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

