# GET /admin/v1/environments/{environmentName}/storageClasses/{storageClassName}/pvcs

**Resource:** [storageClass](../resources/storageClass.md)
**get persistentvolumeclaim list of the storage class**
**Operation ID:** `listStorageClassPvcs`

get the persistentvolumeclaim list related to the specified storage class for the specified environment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Name of the Environment |
| `storageClassName` | path | string | Yes | Name of the Storage Class to be specified |
| `node` | query | string | No | Name of the Node to be specified |
| `orgName` | query | string | No | Name of the Org to be specified |
| `clusterName` | query | string | No | Name of the Cluster to be specified |
| `pageId` | query | integer (int64) | Yes | defined page id. |
| `pageSize` | query | integer (int64) | Yes | defined page size. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully get the  storage class. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the environment or persistentvolumeclaim does not exist. |

