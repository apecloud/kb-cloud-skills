# GET /admin/v1/organizations/{orgName}/backups/{backupId}

**Resource:** [backup](../resources/backup.md)
**Get backup**
**Operation ID:** `getBackup`

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

[backup](../schemas/backup/backup.md)

