# POST /admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}

**Resource:** [backupRepo](../resources/backupRepo.md)
**Update backup repo**
**Operation ID:** `updateBackupRepo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `backupRepoName` | path | string | Yes | name of the BackupRepo |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupRepoUpdate](../schemas/backupRepoUpdate/backupRepoUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupRepo](../schemas/backupRepo/backupRepo.md)

