# DELETE /api/v1/organizations/{orgName}/replication/endpoint/{endpointID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Delete a data endpoint**
**Operation ID:** `deleteDataEndpoint`

Delete a data endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `endpointID` | path | string | Yes | The ID of the data endpoint |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when endpoint is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

