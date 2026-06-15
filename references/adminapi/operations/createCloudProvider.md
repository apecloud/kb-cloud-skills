# POST /admin/v1/providers

**Resource:** [provider](../resources/provider.md)
**Create a cloud provider**
**Operation ID:** `createCloudProvider`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [providerCreate](../schemas/providerCreate/providerCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[provider](../schemas/provider/provider.md)

