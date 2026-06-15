# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/parameterHistories

**Resource:** [parameter](../resources/parameter.md)
**List parameters history of the cluster**
**Operation ID:** `listParametersHistory`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `parameterName` | query | string | No | name of the parameter |
| `component` | query | string | Yes | component type |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get parameters history of the cluster successfully |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[parameterHistoryList](../schemas/parameterHistoryList/parameterHistoryList.md)

