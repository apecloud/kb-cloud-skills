# GET /api/v1/organizations/{orgName}/clustersWithDelete/restoreTimeRange

**Resource:** [restore](../resources/restore.md)
**Get cluster restore time ragne**
**Operation ID:** `getRestoreTimeRange`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterID` | query | string | Yes | ID of the KubeBlocks cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backup](../schemas/backup/backup.md)

