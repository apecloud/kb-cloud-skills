# GET /api/v1/organizations/{orgName}/replication/endpoint/{endpointID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Get Data Endpoint Details**
**Operation ID:** `getDataEndpoint`

Retrieve a data endpoint detail.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `endpointID` | path | string | Yes | The ID of the data endpoint |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A detail of data endpoint. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataChannelListEndpoint](../schemas/dataChannelListEndpoint/dataChannelListEndpoint.md)

