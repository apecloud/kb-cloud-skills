# GET /api/v1/organizations/{orgName}/tasks

**Resource:** [task](../resources/task.md)
**List task**
**Operation ID:** `listTasks`

List tasks

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `resourceId` | query | string | No | Filter by resource ID (such as cluster ID, environment ID, etc.) |
| `resourceType` | query | string | No | Filter by resource type |
| `taskType` | query | string | No | Filter by task type (supports multiple task types separated by commas, e.g., "cluster-scale,cluster-upgrade") |
| `status` | query | string | No | Filter by task status (supports multiple statuses separated by commas, e.g., "Running,Pending") |
| `pageNumber` | query | integer (int64) | No | The pageNumber of the query |
| `pageSize` | query | integer (int64) | No | The pageSize of the query |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Current task list |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[taskList](../schemas/taskList/taskList.md)

