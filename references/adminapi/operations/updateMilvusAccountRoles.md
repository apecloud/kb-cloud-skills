# PUT /admin/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles

**Resource:** [milvus](../resources/milvus.md)
**Update Milvus account roles**
**Operation ID:** `updateMilvusAccountRoles`

Replace a Milvus account's role assignments.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the Account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MilvusAccountRoles](../schemas/Milvus/MilvusAccountRoles.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

