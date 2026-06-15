# DELETE /api/v1/organizations/{orgName}/checks/{checkID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Delete a data check**
**Operation ID:** `deleteDataCheck`

Delete a standalone data check and its runtime resources.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `checkID` | path | string | Yes | The ID of the check |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when check is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

