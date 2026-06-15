# GET /api/v1/organizations/{orgName}/environments/{environmentName}/storageClasses

**Resource:** [storageClass](../resources/storageClass.md)
**Get storage class stats**
**Operation ID:** `getStorageClassStats`

Provides a summary of storage class statistics, aggregated and organized by namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Organization |
| `environmentName` | path | string | Yes | name of the Environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | Returned when the user does not have permission to access the resource. |
| 404 | Returned when the resource does not exist. |

