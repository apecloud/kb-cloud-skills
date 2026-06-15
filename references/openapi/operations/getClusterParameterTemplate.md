# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/parameterTemplate

**Resource:** [parameterTemplate](../resources/parameterTemplate.md)
**Get cluster parameter template**
**Operation ID:** `getClusterParameterTemplate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `component` | query | string | No | component type |
| `engineName` | query | string | No | engine name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get parameter template applicable to the cluster successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[paramTplApplyToClusterList](../schemas/paramTplApplyToClusterList/paramTplApplyToClusterList.md)

