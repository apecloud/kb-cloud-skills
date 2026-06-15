# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/explain

**Resource:** [dms](../resources/dms.md)
**explain a MongoDB query**
**Operation ID:** `mongoExplain`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [MongoExplainRequest](../schemas/Mongo/MongoExplainRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema:**

[MongoExplainResponse](../schemas/Mongo/MongoExplainResponse.md)

