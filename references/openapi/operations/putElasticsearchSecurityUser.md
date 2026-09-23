# PUT /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Create or update Elasticsearch security user**
**Operation ID:** `putElasticsearchSecurityUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ESPutSecurityUserRequest](../schemas/ESPutSecurityUserRequest/ESPutSecurityUserRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Create or update Elasticsearch security user successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

