# GET /api/v1/environments/{environmentName}/storages/{storageName}

**Resource:** [storage](../resources/storage.md)
**Get a storage**
**Operation ID:** `getStorage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `storageName` | path | string | Yes | name of the storage |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[storage](../schemas/storage/storage.md)

