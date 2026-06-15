# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}

**Resource:** [dms](../resources/dms.md)
**get the datasource**
**Operation ID:** `getDataSourceV2`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[datasource](../schemas/datasource/datasource.md)

