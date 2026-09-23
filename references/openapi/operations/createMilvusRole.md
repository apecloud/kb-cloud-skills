# POST /api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles

**Resource:** [milvus](../resources/milvus.md)
**Create Milvus role**
**Operation ID:** `createMilvusRole`

Create a Milvus native role and grant its initial privileges.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MilvusRoleCreateRequest](../schemas/Milvus/MilvusRoleCreateRequest.md)

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

