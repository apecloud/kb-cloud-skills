# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}/parameters

**Resource:** [dms](../resources/dms.md)
**list cluster parameters**
**Operation ID:** `listParameters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `tenantId` | path | string | Yes |  |
| `mode` | query | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsParameterList](../schemas/Dms/DmsParameterList.md)

