# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy

**Resource:** [backup](../resources/backup.md)
**Get backup policy**
**Operation ID:** `getClusterBackupPolicy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `useVolumeSnapshot` | query | boolean | No | use volume snapshot to back up |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[backupPolicy](../schemas/backupPolicy/backupPolicy.md)

