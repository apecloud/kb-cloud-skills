# GET /api/v1/organizations/{orgName}/replication/channel/parameters

**Resource:** [dataReplication](../resources/dataReplication.md)
**List Data Channel Parameters**
**Operation ID:** `listDataChannelParameters`

Retrieve a list of data channel parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `standardName` | query | string | No | The name of the standard definition |
| `channelID` | query | string | No | The ID of the data channel |
| `source` | query | string | No | The source EngineDeifnition name |
| `target` | query | string | No | The target EngineDeifnition name |
| `moduleName` | query | string | No | The module name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A list of data channel parameters. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dataReplicationParametersResponse](../schemas/dataReplicationParametersResponse/dataReplicationParametersResponse.md)

