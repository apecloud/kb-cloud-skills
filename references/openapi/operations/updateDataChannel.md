# PATCH /api/v1/organizations/{orgName}/replication/channel/{channelID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Update a data channel**
**Operation ID:** `updateDataChannel`

Update a new data channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes | The ID of the data channel |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dataReplicationUpdate](../schemas/dataReplicationUpdate/dataReplicationUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataChannelResponse](../schemas/dataChannelResponse/dataChannelResponse.md)

