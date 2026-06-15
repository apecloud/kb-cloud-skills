# GET /api/v1/environments/{environmentName}/backupRepo/{backupRepoName}

**Resource:** [backupRepo](../resources/backupRepo.md)
**Get backup repo**
**Operation ID:** `getBackupRepo`

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
| 404 | (reference) |

**Success Response Schema:**

[backupRepo](../schemas/backupRepo/backupRepo.md)

