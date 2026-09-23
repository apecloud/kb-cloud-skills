# PATCH /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}/unlock

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Unlock Elasticsearch account**
**Operation ID:** `unlockElasticsearchSecurityUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Unlock Elasticsearch account successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

