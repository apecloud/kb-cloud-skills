# DELETE /admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}

**Resource:** [backupRepo](../resources/backupRepo.md)
**Delete backup repo**
**Operation ID:** `deleteBackupRepo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `backupRepoName` | path | string | Yes | name of the BackupRepo |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |

