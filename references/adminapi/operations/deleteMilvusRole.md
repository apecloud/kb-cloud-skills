# DELETE /admin/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [milvus](../resources/milvus.md)
**Delete Milvus role**
**Operation ID:** `deleteMilvusRole`

Delete a Milvus native role.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `roleName` | path | string | Yes | name of the Milvus role |

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

