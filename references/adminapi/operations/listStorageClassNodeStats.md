# GET /admin/v1/environments/{environmentName}/storageClasses/{storageClassName}/nodeStats

**Resource:** [storageClass](../resources/storageClass.md)
**get node stats of the storage class**
**Operation ID:** `listStorageClassNodeStats`

get the node stats related to the specified storage class for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Name of the Environment |
| `storageClassName` | path | string | Yes | Name of the Storage Class to be specified |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully get the node stats of the storage class. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[storageClassNodeStatsList](../schemas/storageClassNodeStatsList/storageClassNodeStatsList.md)

