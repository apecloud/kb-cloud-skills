# GET /admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}/stats

**Resource:** [backupRepo](../resources/backupRepo.md)
**list backup repo stats**
**Operation ID:** `listBackupRepoStats`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `backupRepoName` | path | string | Yes | name of the environment |
| `start` | query | string | No | the start time |
| `end` | query | string | No | the end time |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[backupRepoStatsList](../schemas/backupRepoStatsList/backupRepoStatsList.md)

