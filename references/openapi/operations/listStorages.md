# GET /api/v1/environments/{environmentName}/storages

**Resource:** [storage](../resources/storage.md)
**List storages**
**Operation ID:** `listStorages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |
| `name` | query | string | No | the search key to search storage's name |
| `key` | query | string | No | key to search storage's tag |
| `value` | query | string | No | value to search storage's tag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[storageList](../schemas/storageList/storageList.md)

