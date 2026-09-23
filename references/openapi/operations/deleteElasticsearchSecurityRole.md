# DELETE /api/v1/data/elasticsearch/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [elasticsearch](../resources/elasticsearch.md)
**Delete Elasticsearch security role**
**Operation ID:** `deleteElasticsearchSecurityRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete Elasticsearch security role successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

