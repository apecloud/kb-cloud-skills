# POST /api/v1/organizations/{orgName}/backups/{backupId}/view

**Resource:** [backup](../resources/backup.md)
**view backup info**
**Operation ID:** `viewBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the org |
| `backupId` | path | string | Yes | the id of backup |

## Request Body

**Content Types:** `application/json`

**Schema:** [backupView](../schemas/backupView/backupView.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

