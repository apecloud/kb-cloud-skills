# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/tasks

**Resource:** [dms](../resources/dms.md)
**Get the task list**
**Operation ID:** `GetTaskList`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the task list success |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsTaskList](../schemas/Dms/DmsTaskList.md)

