# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/parameters

**Resource:** [parameter](../resources/parameter.md)
**List parameter properties of the cluster**
**Operation ID:** `listParameterProps`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `component` | query | string | No | component type |
| `rawContent` | query | boolean | No | whether to return the raw template content |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get configuration of the cluster successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[parameterList](../schemas/parameterList/parameterList.md)

