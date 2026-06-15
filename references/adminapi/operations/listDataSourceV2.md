# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource

**Resource:** [dms](../resources/dms.md)
**list the datasource of a cluster**
**Operation ID:** `listDataSourceV2`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[datasourceList](../schemas/datasourceList/datasourceList.md)

