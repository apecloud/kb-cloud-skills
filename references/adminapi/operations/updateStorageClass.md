# PATCH /admin/v1/environments/{environmentName}/storageClasses/{storageClassName}

**Resource:** [storageClass](../resources/storageClass.md)
**Update storage class**
**Operation ID:** `updateStorageClass`

Updates the  storage class for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Name of the Environment |
| `storageClassName` | path | string | Yes | Name of the Storage Class to be updated |

## Request Body

Fields to update for the storage class

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [storageClassUpdate](../schemas/storageClassUpdate/storageClassUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully set the default storage class. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the environment or storage class does not exist. |

