# PATCH /admin/v1/organizations/{orgName}/replication/endpoint/{endpointID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Update a data endpoint**
**Operation ID:** `updateDataEndpoint`

Update an existing data endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `endpointID` | path | string | Yes | The ID of the data endpoint |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dataEndpointCreate](../schemas/dataEndpointCreate/dataEndpointCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataEndpointResponse](../schemas/dataEndpointResponse/dataEndpointResponse.md)

