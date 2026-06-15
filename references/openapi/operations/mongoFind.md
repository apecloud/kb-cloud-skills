# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/find

**Resource:** [dms](../resources/dms.md)
**find documents in a MongoDB collection**
**Operation ID:** `mongoFind`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `db` | path | string | Yes | database name |
| `col` | path | string | Yes | collection name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoFindRequest](../schemas/Mongo/MongoFindRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoFindResponse](../schemas/Mongo/MongoFindResponse.md)

