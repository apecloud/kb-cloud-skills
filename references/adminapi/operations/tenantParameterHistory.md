# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameterHistory

**Resource:** [dms](../resources/dms.md)
**List parameters history of the Oceanbase tenant**
**Operation ID:** `tenantParameterHistory`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `tenantId` | path | string | Yes | id of the tenant |
| `parameterName` | query | string | No | name of the parameter |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get parameters history of the cluster successfully |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[parameterHistoryList](../schemas/parameterHistoryList/parameterHistoryList.md)

