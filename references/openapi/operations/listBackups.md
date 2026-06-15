# GET /api/v1/organizations/{orgName}/backups

**Resource:** [backup](../resources/backup.md)
**List backups**
**Operation ID:** `listBackups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | query | string | No | cluster name of the Backup |
| `clusterID` | query | string | No | cluster ID of the Backup |
| `backupRepo` | query | string | No | backup repo of the Backup |
| `fetchWithDeletedCluster` | query | boolean | No | defined whether to search for deleted clusters. if not set, returns all backups |
| `withDeletedBackups` | query | boolean | No | defined whether to search for deleted backups. if not set, only return backups that are not deleted |
| `withRestoreCluster` | query | boolean | No | defined whether to search for restore backups. |
| `backupType` | query | string | No | type of the backup |
| `withRebuildInstance` | query | boolean | No | defined whether to search for rebuilding instance. |
| `withHScale` | query | boolean | No | defined whether to search for hScale instance. |
| `componentName` | query | string | No | get the backups belong to the component |
| `page` | query | integer | No | page number |
| `pageSize` | query | integer | No | page size |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupList](../schemas/backupList/backupList.md)

