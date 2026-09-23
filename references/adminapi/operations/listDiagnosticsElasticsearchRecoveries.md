# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/recoveries

**Resource:** [diagnostics](../resources/diagnostics.md)
**List active Elasticsearch shard recoveries**
**Operation ID:** `listDiagnosticsElasticsearchRecoveries`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `index` | query | string | No | Index name or pattern |
| `node` | query | string | No | Exact target node ID or name |

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

[elasticsearchRecoveryList](../schemas/elasticsearchRecoveryList/elasticsearchRecoveryList.md)

