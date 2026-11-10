# GET /admin/v1/replication/endpoints

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Endpoints**
**Operation ID:** `listAdminDataEndpoints`

Retrieve a list of data endpoints.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | The Name of the organization |
| `name` | query | string | No | The name of the data endpoint |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of data endpoints. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataEndpointList](../schemas/dataEndpointList/dataEndpointList.md)

