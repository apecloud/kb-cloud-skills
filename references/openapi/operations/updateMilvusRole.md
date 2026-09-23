# PUT /api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [milvus](../resources/milvus.md)
**Update Milvus role**
**Operation ID:** `updateMilvusRole`

Update an existing Milvus native role by replacing its privilege grants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `roleName` | path | string | Yes | name of the Milvus role |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MilvusRoleRequest](../schemas/Milvus/MilvusRoleRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[MilvusRole](../schemas/Milvus/MilvusRole.md)

