# POST /api/v1/organizations/{orgName}/backups/batch-delete

**Resource:** [backup](../resources/backup.md)
**Batch delete backups**
**Operation ID:** `batchDeleteBackups`

Delete multiple backups in a single request. Backups which cannot be deleted are reported in the error response and do not roll back the backups that were already deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupBatchDelete](../schemas/backupBatchDelete/backupBatchDelete.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when the backups are deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

