# POST /admin/v1/environments/{environmentName}/storages/{storageName}

**Resource:** [storage](../resources/storage.md)
**Update a storage**
**Operation ID:** `updateStorage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `storageName` | path | string | Yes | name of storage |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [storageUpdate](../schemas/storageUpdate/storageUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[storage](../schemas/storage/storage.md)

