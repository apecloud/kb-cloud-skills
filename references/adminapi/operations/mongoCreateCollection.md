# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}

**Resource:** [dms](../resources/dms.md)
**create MongoDB collection**
**Operation ID:** `mongoCreateCollection`

Creates a collection. Creating the first collection in a database is the supported Create Database backend semantic.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |
| `db` | path | string | Yes | database name |
| `col` | path | string | Yes | initial collection name |

## Request Body

**Content Types:** `application/json`

**Schema:** [MongoCreateCollectionRequest](../schemas/Mongo/MongoCreateCollectionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | collection created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[MongoCollectionInfo](../schemas/Mongo/MongoCollectionInfo.md)

