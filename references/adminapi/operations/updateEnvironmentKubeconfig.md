# POST /admin/v1/environments/{environmentName}/kubeconfig

**Resource:** [environment](../resources/environment.md)
**update environment kubeconfig**
**Operation ID:** `updateEnvironmentKubeconfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Request Body

**Content Types:** `application/json`

**Schema:** [kubeconfig](../schemas/kubeconfig/kubeconfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[httpBody](../schemas/httpBody/httpBody.md)

