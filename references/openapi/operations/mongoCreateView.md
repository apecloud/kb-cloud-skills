# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases/{db}/views

**Resource:** [dms](../resources/dms.md)
**create MongoDB view from a read-only aggregation pipeline**
**Operation ID:** `mongoCreateView`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `id` | path | string | Yes |  |
| `db` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoCreateViewRequest](../schemas/Mongo/MongoCreateViewRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | view created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

