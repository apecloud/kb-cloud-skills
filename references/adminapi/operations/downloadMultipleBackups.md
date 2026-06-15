# POST /admin/v1/organizations/{orgName}/backups/{backupId}/download

**Resource:** [backup](../resources/backup.md)
**Download multiple backup files**
**Operation ID:** `downloadMultipleBackups`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `backupId` | path | string | Yes | the id of backup |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupDownload](../schemas/backupDownload/backupDownload.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response |

