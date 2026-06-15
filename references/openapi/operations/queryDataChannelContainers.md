# GET /api/v1/organizations/{orgName}/replication/channel/{channelID}/containers

**Resource:** [dataReplication](../resources/dataReplication.md)
**Query data channel module pod containers**
**Operation ID:** `queryDataChannelContainers`

Query containers of a data channel module pod

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes |  |
| `moduleName` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of data channel module containers. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataReplicationChannelContainer](../schemas/dataReplicationChannelContainer/dataReplicationChannelContainer.md)

