# GET /api/v1/organizations/{orgName}/replication/channel

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Channels**
**Operation ID:** `listDataChannels`

Retrieve a list of data channels.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `name` | query | string | No | The name of the data channel |
| `status` | query | string[] | No | The status of the data channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of data channels. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataChannelList](../schemas/dataChannelList/dataChannelList.md)

