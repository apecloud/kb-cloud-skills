# GET /api/v1/organizations/{orgName}/replication/channel/{channelID}/events

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Channel Events**
**Operation ID:** `listDataChannelEvents`

Retrieve a list of data channel events.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes | The ID of the data channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of data channel events. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataReplicationEventList](../schemas/dataReplicationEventList/dataReplicationEventList.md)

