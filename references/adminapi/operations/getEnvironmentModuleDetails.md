# GET /admin/v1/environments/{environmentName}/modules/{moduleName}/details

**Resource:** [environment](../resources/environment.md)
**Get details information for an environment module**
**Operation ID:** `getEnvironmentModuleDetails`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Environment Name |
| `moduleName` | path | string | Yes | Environment module name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[environmentModuleDetails](../schemas/environmentModuleDetails/environmentModuleDetails.md)

