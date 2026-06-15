# POST /admin/v1/environments/{environmentName}/storages

**Resource:** [storage](../resources/storage.md)
**Create a storage**
**Operation ID:** `createStorage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [storageCreate](../schemas/storageCreate/storageCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[storage](../schemas/storage/storage.md)

