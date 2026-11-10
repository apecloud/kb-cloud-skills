# dataReplication

Data Replication APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/replication/channel` | List Data Channels | [View](../operations/listDataChannels.md) |
| POST | `/api/v1/organizations/{orgName}/replication/channel` | Create a new data channel | [View](../operations/createDataChannel.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/{channelID}` | Get Data Channel Details | [View](../operations/getDataChannel.md) |
| DELETE | `/api/v1/organizations/{orgName}/replication/channel/{channelID}` | Delete a data channel | [View](../operations/deleteDataChannel.md) |
| PATCH | `/api/v1/organizations/{orgName}/replication/channel/{channelID}` | Update a data channel | [View](../operations/updateDataChannel.md) |
| POST | `/api/v1/organizations/{orgName}/replication/channel/{channelID}/ops/{opsType}` | Create a new data channel ops | [View](../operations/createDataChannelOps.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/{channelID}/events` | List Data Channel Events | [View](../operations/listDataChannelEvents.md) |
| POST | `/api/v1/organizations/{orgName}/replication/channel/objects` | query replication object | [View](../operations/queryReplicationObject.md) |
| POST | `/api/v1/organizations/{orgName}/replication/channel/precheck` | create pre check | [View](../operations/createPreCheck.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}` | get preCheck | [View](../operations/getPreCheck.md) |
| DELETE | `/api/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}` | delete preCheck | [View](../operations/deletePreCheck.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/{channelID}/logs` | Query data channel logs | [View](../operations/queryDataChannelLogs.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/{channelID}/containers` | Query data channel module pod containers | [View](../operations/queryDataChannelContainers.md) |
| GET | `/api/v1/organizations/{orgName}/replication/channel/parameters` | List Data Channel Parameters | [View](../operations/listDataChannelParameters.md) |
| GET | `/api/v1/organizations/{orgName}/replication/endpoints` | List Data Endpoints | [View](../operations/listDataEndpoints.md) |
| POST | `/api/v1/organizations/{orgName}/replication/endpoints` | Create a new data endpoint | [View](../operations/createDataEndpoint.md) |
| GET | `/api/v1/organizations/{orgName}/replication/endpoint/{endpointID}` | Get Data Endpoint Details | [View](../operations/getDataEndpoint.md) |
| DELETE | `/api/v1/organizations/{orgName}/replication/endpoint/{endpointID}` | Delete a data endpoint | [View](../operations/deleteDataEndpoint.md) |
| PATCH | `/api/v1/organizations/{orgName}/replication/endpoint/{endpointID}` | Update a data endpoint | [View](../operations/updateDataEndpoint.md) |
| GET | `/api/v1/organizations/{orgName}/checks` | List Data Checks | [View](../operations/listDataChecks.md) |
| POST | `/api/v1/organizations/{orgName}/checks` | Create a data check | [View](../operations/createDataCheck.md) |
| GET | `/api/v1/organizations/{orgName}/checks/{checkID}` | Get Data Check | [View](../operations/getDataCheck.md) |
| DELETE | `/api/v1/organizations/{orgName}/checks/{checkID}` | Delete a data check | [View](../operations/deleteDataCheck.md) |
| GET | `/api/v1/organizations/{orgName}/checks/{checkID}/details` | Get Data Check Difference Details | [View](../operations/getDataCheckDetails.md) |
| GET | `/api/v1/organizations/{orgName}/checks/{checkID}/sqlLogs` | Get Data Check SQL Logs | [View](../operations/getDataCheckSQLLogs.md) |
