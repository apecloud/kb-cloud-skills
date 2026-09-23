# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/diagnostics/elasticsearch/allocationExplain

**Resource:** [diagnostics](../resources/diagnostics.md)
**Explain Elasticsearch shard allocation**
**Operation ID:** `explainDiagnosticsElasticsearchAllocation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `index` | query | string | Yes |  |
| `shard` | query | integer (int64) | Yes |  |
| `primary` | query | boolean | Yes |  |
| `currentNode` | query | string | No |  |

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

[elasticsearchAllocationExplanation](../schemas/elasticsearchAllocationExplanation/elasticsearchAllocationExplanation.md)

