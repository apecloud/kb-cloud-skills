# GET /admin/v1/organizations/{orgName}/backups/{backupId}/logs

**Resource:** [backup](../resources/backup.md)
**Get backup log**
**Operation ID:** `getBackupLog`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `backupId` | path | string | Yes | id of the Backup |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[backupLog](../schemas/backupLog/backupLog.md)

