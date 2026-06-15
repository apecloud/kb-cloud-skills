# GET /admin/v1/organizations/{orgName}/inspectionTasksByOrg

**Resource:** [inspection](../resources/inspection.md)
**list inspection tasks by org**
**Operation ID:** `listInspectionTasksByOrg`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterId` | query | string | No | list tasks for the specified cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [inspectionTask](../schemas/inspectionTask/inspectionTask.md)

