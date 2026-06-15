# POST /admin/v1/environments/{environmentName}/backupRepo/{backupRepoName}/view

**Resource:** [backupRepo](../resources/backupRepo.md)
**view backup repo**
**Operation ID:** `viewBackupRepo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `backupRepoName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupRepoView](../schemas/backupRepoView/backupRepoView.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

