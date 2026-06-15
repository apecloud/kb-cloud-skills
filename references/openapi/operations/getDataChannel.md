# GET /api/v1/organizations/{orgName}/replication/channel/{channelID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Get Data Channel Details**
**Operation ID:** `getDataChannel`

Retrieve a data channel detail.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes | The ID of the data channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A detail of data channel. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataChannelDetail](../schemas/dataChannelDetail/dataChannelDetail.md)

