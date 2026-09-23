# GET /api/v1/organizations/{orgName}/tasks/{taskId}/events

**Resource:** [event](../resources/event.md)
**List operation events related to a task**
**Operation ID:** `listTaskEvents`

List operation events whose recorded response contains the task ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `taskId` | path | string | Yes | ID of the task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Operation events related to the task |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[eventList](../schemas/eventList/eventList.md)

