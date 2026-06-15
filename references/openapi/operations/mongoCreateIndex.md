# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/indexes

**Resource:** [dms](../resources/dms.md)
**create MongoDB collection index**
**Operation ID:** `mongoCreateIndex`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |
| `col` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoCreateIndexRequest](../schemas/Mongo/MongoCreateIndexRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | index created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

