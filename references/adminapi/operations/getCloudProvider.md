# GET /admin/v1/providers/{providerName}

**Resource:** [provider](../resources/provider.md)
**Get cloud provider**
**Operation ID:** `getCloudProvider`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `providerName` | path | string | Yes | Name of the cloud provider |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[provider](../schemas/provider/provider.md)

