# GET /api/v1/organizations/{orgName}/replication/channel/{channelID}/logs

**Resource:** [dataReplication](../resources/dataReplication.md)
**Query data channel logs**
**Operation ID:** `queryDataChannelLogs`

Query logs of a data channel

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes |  |
| `moduleName` | query | string | No |  |
| `containerName` | query | string | No |  |
| `limit` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | channel logs output |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

