# GET /admin/v1/environments/{environmentName}/inspectionTasksByEnv

**Resource:** [inspection](../resources/inspection.md)
**list inspection tasks by env**
**Operation ID:** `listInspectionTasksByEnv`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `nodeName` | query | string | No | list tasks for the specified node |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [inspectionTask](../schemas/inspectionTask/inspectionTask.md)

