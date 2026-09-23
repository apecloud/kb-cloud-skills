# PATCH /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Change Elasticsearch account password**
**Operation ID:** `changeElasticsearchSecurityUserPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ESSecurityPasswordRequest](../schemas/ESSecurityPasswordRequest/ESSecurityPasswordRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Change Elasticsearch account password successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

