# DELETE /admin/v1/environments/{environmentName}/storages/{storageName}

**Resource:** [storage](../resources/storage.md)
**Delete a storage**
**Operation ID:** `deleteStorage`

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

