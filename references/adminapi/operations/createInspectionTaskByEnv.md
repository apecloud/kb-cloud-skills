# POST /admin/v1/environments/{environmentName}/inspectionTasksByEnv

**Resource:** [inspection](../resources/inspection.md)
**create inspection task by env**
**Operation ID:** `createInspectionTaskByEnv`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [inspectionTask](../schemas/inspectionTask/inspectionTask.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | No content. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

