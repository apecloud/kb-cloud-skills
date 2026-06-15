# GET /admin/v1/environments/{environmentName}/bootstrapManifests

**Resource:** [environment](../resources/environment.md)
**Get bootstrap manifests of an environment**
**Operation ID:** `getEnvironmentBootstrapManifests`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[httpBody](../schemas/httpBody/httpBody.md)

