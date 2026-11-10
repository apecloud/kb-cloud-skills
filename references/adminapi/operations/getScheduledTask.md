# GET /admin/v1/scheduled-tasks/{scheduledTaskId}

**Resource:** [task](../resources/task.md)
**Get scheduled task**
**Operation ID:** `getScheduledTask`

Get scheduled task details

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `scheduledTaskId` | path | string | Yes | ID of the scheduled task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Scheduled task details |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[scheduledTaskDetail](../schemas/scheduledTaskDetail/scheduledTaskDetail.md)

