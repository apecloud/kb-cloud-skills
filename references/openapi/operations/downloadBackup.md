# GET /api/v1/organizations/{orgName}/backups/{backupId}/download

**Resource:** [backup](../resources/backup.md)
**Download full backup**
**Operation ID:** `downloadBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `backupId` | path | string | Yes | the id of backup |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response |

