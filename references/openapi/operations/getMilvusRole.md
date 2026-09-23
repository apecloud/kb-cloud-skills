# GET /api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [milvus](../resources/milvus.md)
**Get Milvus role**
**Operation ID:** `getMilvusRole`

Get a Milvus native role and its privilege grants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `roleName` | path | string | Yes | name of the Milvus role |

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

[MilvusRole](../schemas/Milvus/MilvusRole.md)

