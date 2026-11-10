# PATCH /admin/v1/tasks/{taskId}/retry

**Resource:** [task](../resources/task.md)
**Retry a task**
**Operation ID:** `retryTask`

Restart a failed or stopped task. Resume requires the task type to declare resume in allowActions. The default mode is restart, which reruns all steps; resume preserves successful steps.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `taskId` | path | string | Yes | ID of the task |
| `mode` | query | taskRetryMode | No | restart reruns all steps; resume preserves successful steps and reruns unfinished steps and PreFinish hooks. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Current status of the task |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | The task type does not support resume. |
| 500 | (reference) |

**Success Response Schema:**

[task](../schemas/task/task.md)

