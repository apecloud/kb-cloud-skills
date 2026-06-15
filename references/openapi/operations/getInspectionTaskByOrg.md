# GET /api/v1/organizations/{orgName}/inspectionTasksByOrg/{taskId}

**Resource:** [inspection](../resources/inspection.md)
**get inspection task by org**
**Operation ID:** `getInspectionTaskByOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
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

[inspectionTask](../schemas/inspectionTask/inspectionTask.md)

