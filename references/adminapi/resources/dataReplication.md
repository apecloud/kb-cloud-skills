# dataReplication

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/replication/channel` | List Data Channels | [View](../operations/listAdminDataChannels.md) |
| POST | `/admin/v1/organizations/{orgName}/replication/channel` | Create a new data channel | [View](../operations/createAdminDataChannel.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}` | Get Data Channel Details | [View](../operations/getDataChannel.md) |
| DELETE | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}` | Delete a data channel | [View](../operations/deleteDataChannel.md) |
| PATCH | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}` | Update a data channel | [View](../operations/updateDataChannel.md) |
| POST | `/admin/v1/organizations/{orgName}/replication/channel/objects` | query replication object | [View](../operations/queryReplicationObject.md) |
| POST | `/admin/v1/organizations/{orgName}/replication/channel/precheck` | create pre check | [View](../operations/createPreCheck.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}` | get preCheck | [View](../operations/getPreCheck.md) |
| DELETE | `/admin/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}` | delete preCheck | [View](../operations/deletePreCheck.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}/logs` | Query data channel logs | [View](../operations/queryDataChannelLogs.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}/containers` | Query data channel module pod containers | [View](../operations/queryDataChannelContainers.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/parameters` | List Data Channel Parameters | [View](../operations/listDataChannelParameters.md) |
| GET | `/admin/v1/checks` | List Data Checks | [View](../operations/listAdminDataChecks.md) |
| POST | `/admin/v1/organizations/{orgName}/checks` | Create a data check | [View](../operations/createAdminDataCheck.md) |
| GET | `/admin/v1/organizations/{orgName}/checks/{checkID}` | Get Data Check | [View](../operations/getDataCheck.md) |
| DELETE | `/admin/v1/organizations/{orgName}/checks/{checkID}` | Delete a data check | [View](../operations/deleteDataCheck.md) |
| GET | `/admin/v1/organizations/{orgName}/checks/{checkID}/details` | Get Data Check Difference Details | [View](../operations/getDataCheckDetails.md) |
| GET | `/admin/v1/organizations/{orgName}/checks/{checkID}/sqlLogs` | Get Data Check SQL Logs | [View](../operations/getDataCheckSQLLogs.md) |
| POST | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}/ops/{opsType}` | Create a new data channel ops | [View](../operations/createDataChannelOps.md) |
| GET | `/admin/v1/organizations/{orgName}/replication/channel/{channelID}/events` | List Data Channel Events | [View](../operations/listDataChannelEvents.md) |
