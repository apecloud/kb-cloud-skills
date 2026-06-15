# PATCH /api/v1/organizations/{orgName}/clusters/{clusterName}/backupPolicy

**Resource:** [backup](../resources/backup.md)
**Update backup policy**
**Operation ID:** `updateBackupPolicy`

partially update the specified Backup Policy

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `useVolumeSnapshot` | query | boolean | No | use volume snapshot to back up |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupPolicy](../schemas/backupPolicy/backupPolicy.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned when project is deleted successfully. |
| 401 | (reference) |

**Success Response Schema:**

[backupPolicy](../schemas/backupPolicy/backupPolicy.md)

