# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}

**Resource:** [dms](../resources/dms.md)
**get MongoDB collection stats**
**Operation ID:** `getMongoCollection`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `db` | path | string | Yes | database name |
| `col` | path | string | Yes | collection name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoCollectionStats](../schemas/Mongo/MongoCollectionStats.md)

