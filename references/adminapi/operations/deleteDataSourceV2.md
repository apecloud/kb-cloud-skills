# DELETE /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}

**Resource:** [dms](../resources/dms.md)
**delete the datasource**
**Operation ID:** `deleteDataSourceV2`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when datasource is deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

