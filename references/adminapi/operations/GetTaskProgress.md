# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/task

**Resource:** [dms](../resources/dms.md)
**Get the task progress**
**Operation ID:** `GetTaskProgress`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `taskId` | query | string | Yes | the task id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the task success |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsTaskInfo](../schemas/Dms/DmsTaskInfo.md)

