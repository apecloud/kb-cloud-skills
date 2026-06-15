# GET /api/v1/environments/{environmentName}/modules

**Resource:** [environment](../resources/environment.md)
**Get environment module information in an environment**
**Operation ID:** `getEnvironmentModuleInfo`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | Environment Name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[environmentModuleInfo](../schemas/environmentModuleInfo/environmentModuleInfo.md)

