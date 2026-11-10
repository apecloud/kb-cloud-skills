# GET /api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/databases/{database}/collections

**Resource:** [mongodb](../resources/mongodb.md)
**List MongoDB cluster database objects**
**Operation ID:** `mongoListClusterCollections`

Lists existing collections, views and time-series collections in a database using the cluster management connection. Returns metadata, not document contents.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `database` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Database objects; an empty database returns an empty array. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [MongoCollectionInfo](../schemas/Mongo/MongoCollectionInfo.md)

