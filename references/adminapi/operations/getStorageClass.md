# GET /admin/v1/environments/{environmentName}/storageClasses/{storageClassName}

**Resource:** [storageClass](../resources/storageClass.md)
**get storage class**
**Operation ID:** `getStorageClass`

get the storage class for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Name of the Environment |
| `storageClassName` | path | string | Yes | Name of the Storage Class to be updated |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully get the  storage class. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the environment or storage class does not exist. |

