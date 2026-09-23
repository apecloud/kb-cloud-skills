# GET /admin/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles

**Resource:** [milvus](../resources/milvus.md)
**List Milvus roles**
**Operation ID:** `listMilvusRoles`

List Milvus native roles and their privilege grants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[MilvusRoleList](../schemas/Milvus/MilvusRoleList.md)

