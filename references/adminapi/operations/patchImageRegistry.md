# PATCH /admin/v1/imageRegistries/{imageRegistryName}

**Resource:** [imageRegistry](../resources/imageRegistry.md)
**Update image registry**
**Operation ID:** `patchImageRegistry`

partially update the specified image registry

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `imageRegistryName` | path | string | Yes | name of the image registry |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [imageRegistry](../schemas/imageRegistry/imageRegistry.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[imageRegistry](../schemas/imageRegistry/imageRegistry.md)

