# POST /admin/v1/environments/{environmentName}/storages/{storageName}/importbackup

**Resource:** [storage](../resources/storage.md)
**scan and import backup records from storage**
**Operation ID:** `importBackup`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `storageName` | path | string | Yes | name of the storage |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [importBackup](../schemas/importBackup/importBackup.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[backupList](../schemas/backupList/backupList.md)

