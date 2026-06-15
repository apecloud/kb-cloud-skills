# GET /admin/v1/environments/{environmentName}/storageClasses

**Resource:** [storageClass](../resources/storageClass.md)
**List storage classes of a environment**
**Operation ID:** `listStorageClasses`

Provides a summary of storage class statistics.

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

