# DELETE /api/v1/organizations/{orgName}/replication/channel/precheck/{preCheckID}

**Resource:** [dataReplication](../resources/dataReplication.md)
**delete preCheck**
**Operation ID:** `deletePreCheck`
⚠️ **Deprecated**

delete preCheck.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `preCheckID` | path | string | Yes | The ID of the preCheck task |
| `orgName` | path | string | Yes | The Name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when preCheck is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

