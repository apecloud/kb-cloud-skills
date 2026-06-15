# GET /admin/v1/environments/{environmentName}/storageProvisioners

**Resource:** [storageClass](../resources/storageClass.md)
**List the provisioners that can be used by storage class of a environment**
**Operation ID:** `listStorageProvisioners`

Provides a summary of storage provisioners statistics.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the resource does not exist. |

