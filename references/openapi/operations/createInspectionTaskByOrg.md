# POST /api/v1/organizations/{orgName}/inspectionTasksByOrg

**Resource:** [inspection](../resources/inspection.md)
**create inspection task by org**
**Operation ID:** `createInspectionTaskByOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

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

