# POST /api/v1/organizations/{orgName}/replication/channel

**Resource:** [dataReplication](../resources/dataReplication.md)
**Create a new data channel**
**Operation ID:** `createDataChannel`

Create a new data channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dataReplicationCreate](../schemas/dataReplicationCreate/dataReplicationCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataChannelResponse](../schemas/dataChannelResponse/dataChannelResponse.md)

