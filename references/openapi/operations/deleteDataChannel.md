# DELETE /api/v1/organizations/{orgName}/replication/channel/{channelID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**Delete a data channel**
**Operation ID:** `deleteDataChannel`

Delete a data channel.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The Name of the organization |
| `channelID` | path | string | Yes | The ID of the data channel |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when channel is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

