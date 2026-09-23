# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/shards

**Resource:** [diagnostics](../resources/diagnostics.md)
**List Elasticsearch shards**
**Operation ID:** `listDiagnosticsElasticsearchShards`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `index` | query | string | No | Index name or pattern |
| `node` | query | string | No | Exact node ID or name |
| `state` | query | elasticsearchShardState | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[elasticsearchShardList](../schemas/elasticsearchShardList/elasticsearchShardList.md)

