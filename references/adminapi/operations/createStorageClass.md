# POST /admin/v1/environments/{environmentName}/storageClasses

**Resource:** [storageClass](../resources/storageClass.md)
**create storage class**
**Operation ID:** `createStorageClass`

Create storage class for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Name of the Environment |

## Request Body

Fields used to create the storage class

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [storageClassCreate](../schemas/storageClassCreate/storageClassCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully create the storage class. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the resource does not exist. |

