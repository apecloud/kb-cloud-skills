# POST /api/v1/organizations/{orgName}/replication/channel/{channelID}/ops/{opsType}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Create a new data channel ops**
**Operation ID:** `createDataChannelOps`

Create a new data channel ops.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes | The ID of the data channel |
| `opsType` | path | dataReplicationOpsType | Yes | The operation type |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when operation is completed successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

