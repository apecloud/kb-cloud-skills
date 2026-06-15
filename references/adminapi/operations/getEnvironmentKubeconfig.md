# GET /admin/v1/environments/{environmentName}/kubeconfig

**Resource:** [environment](../resources/environment.md)
**Get environment kubeconfig**
**Operation ID:** `getEnvironmentKubeconfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[httpBody](../schemas/httpBody/httpBody.md)

