# POST /admin/v1/organizations/{orgName}/replication/endpoint

**Resource:** [dataReplication](../resources/dataReplication.md)
**Create a new data endpoint**
**Operation ID:** `createAdminDataEndpoint`

Create a new data endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |

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

