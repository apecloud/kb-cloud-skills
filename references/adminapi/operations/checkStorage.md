# POST /admin/v1/storageCheck

**Resource:** [storage](../resources/storage.md)
**Check if storage can be accessed**
**Operation ID:** `checkStorage`

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

[storageCheckResult](../schemas/storageCheckResult/storageCheckResult.md)

