# POST /api/v1/organizations/{orgName}/inspectionTasksByOrg

**Resource:** [inspection](../resources/inspection.md)
**Trigger inspection for selected clusters in an organization**
**Operation ID:** `createInspectionTaskByOrg`

Creates one inspection task per matching non-stopped cluster in the path organization. Omit engines or pass an empty array to select all engines. Omit clusterIDs or pass an empty array to select all clusters. When both arrays are non-empty, clusters must match both filters. All tasks and items are persisted in one transaction before asynchronous execution starts.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [inspectionTaskCreate](../schemas/inspectionTaskCreate/inspectionTaskCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Inspection tasks created and accepted for asynchronous execution. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

