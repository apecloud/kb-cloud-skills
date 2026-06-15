# GET /api/v1/organizations/{orgName}/backupStats

**Resource:** [backup](../resources/backup.md)
**Get backup statistics**
**Operation ID:** `getBackupStats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterID` | query | string | No | id of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupStats](../schemas/backupStats/backupStats.md)

