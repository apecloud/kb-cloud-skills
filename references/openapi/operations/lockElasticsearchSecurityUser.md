# PATCH /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/{username}/lock

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Lock Elasticsearch account**
**Operation ID:** `lockElasticsearchSecurityUser`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `username` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Lock Elasticsearch account successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

