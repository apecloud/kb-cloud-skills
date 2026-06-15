# PATCH /admin/v1/providers/{providerName}

**Resource:** [provider](../resources/provider.md)
**Update a cloud provider**
**Operation ID:** `updateCloudProvider`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `providerName` | path | string | Yes | Name of the cloud provider |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [providerUpdate](../schemas/providerUpdate/providerUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[provider](../schemas/provider/provider.md)

