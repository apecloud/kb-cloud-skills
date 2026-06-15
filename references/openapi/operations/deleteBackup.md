# DELETE /api/v1/organizations/{orgName}/backups/{backupId}

**Resource:** [backup](../resources/backup.md)
**Delete backup**
**Operation ID:** `deleteBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `backupId` | path | string | Yes | id of the Backup |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

