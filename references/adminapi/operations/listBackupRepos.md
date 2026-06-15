# GET /admin/v1/environments/{environmentName}/backupRepo

**Resource:** [backupRepo](../resources/backupRepo.md)
**List backup repos**
**Operation ID:** `listBackupRepos`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupRepoList](../schemas/backupRepoList/backupRepoList.md)

