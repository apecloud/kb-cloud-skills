# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections

**Resource:** [dms](../resources/dms.md)
**list collections in a MongoDB database**
**Operation ID:** `listMongoCollections`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `db` | path | string | Yes | database name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

Array of [MongoCollectionInfo](../schemas/Mongo/MongoCollectionInfo.md)

