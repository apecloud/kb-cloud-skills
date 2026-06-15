# POST /api/v1/organizations/{orgName}/tasks/{taskId}/cancel

**Resource:** [task](../resources/task.md)
**Cancel a task**
**Operation ID:** `cancelTask`

Cancel a task by taskID within the organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
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

