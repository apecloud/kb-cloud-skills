# GET /admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}/check

**Resource:** [backupRepo](../resources/backupRepo.md)
**check backup repo**
**Operation ID:** `checkBackupRepo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `backupRepoName` | path | string | Yes | name of the BackupRepo |
| `orgName` | query | string | No | name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupRepoCheck](../schemas/backupRepoCheck/backupRepoCheck.md)

