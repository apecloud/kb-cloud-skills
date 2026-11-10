# POST /api/v1/organizations/{orgName}/tasks/{taskId}/abort

**Resource:** [task](../resources/task.md)
**Force abort a task**
**Operation ID:** `abortTask`

Forcefully abort a running task. Pending steps or OpsRequests are cancelled, running ones are aborted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `taskId` | path | string | Yes | ID of the task |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Task aborted successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

