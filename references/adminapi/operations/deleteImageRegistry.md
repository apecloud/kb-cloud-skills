# DELETE /admin/v1/imageRegistries/{imageRegistryName}

**Resource:** [imageRegistry](../resources/imageRegistry.md)
**Delete image registry**
**Operation ID:** `deleteImageRegistry`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `imageRegistryName` | path | string | Yes | name of the image registry |

## Request Body

**Content Types:** `application/json`

**Schema:** [imageRegistry](../schemas/imageRegistry/imageRegistry.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

