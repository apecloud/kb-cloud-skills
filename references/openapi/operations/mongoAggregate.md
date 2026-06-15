# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/collections/{col}/aggregate

**Resource:** [dms](../resources/dms.md)
**run MongoDB aggregation pipeline preview**
**Operation ID:** `mongoAggregate`

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

**Schema:** [MongoAggregateRequest](../schemas/Mongo/MongoAggregateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoFindResponse](../schemas/Mongo/MongoFindResponse.md)

