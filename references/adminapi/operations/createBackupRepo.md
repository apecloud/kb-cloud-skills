# POST /admin/v1/environments/{environmentName}/backupRepo

**Resource:** [backupRepo](../resources/backupRepo.md)
**Create backup repo**
**Operation ID:** `createBackupRepo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [backupRepoCreate](../schemas/backupRepoCreate/backupRepoCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 201 | Returned when edge is created successfully. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupRepo](../schemas/backupRepo/backupRepo.md)

