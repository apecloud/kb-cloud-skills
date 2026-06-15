# GET /admin/v1/imageRegistries/{imageRegistryName}

**Resource:** [imageRegistry](../resources/imageRegistry.md)
**Get image registry**
**Operation ID:** `getImageRegistry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `imageRegistryName` | path | string | Yes | name of the image registry |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[imageRegistry](../schemas/imageRegistry/imageRegistry.md)

