# GET /admin/v1/environments/{environmentName}/inspectionTasksByEnv/{taskId}

**Resource:** [inspection](../resources/inspection.md)
**get inspection task by env**
**Operation ID:** `getInspectionTaskByEnv`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `taskId` | path | string | Yes | list task details if specified |
| `format` | query | inspectionTaskFormat | No | the format of the task |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [inspectionTaskItem](../schemas/inspectionTaskItem/inspectionTaskItem.md)

