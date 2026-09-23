# GET /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Get Elasticsearch security user**
**Operation ID:** `getElasticsearchSecurityUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Elasticsearch security user successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ESSecurityUser](../schemas/ESSecurityUser/ESSecurityUser.md)

