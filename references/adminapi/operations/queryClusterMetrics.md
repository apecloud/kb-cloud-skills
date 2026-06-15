# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/metrics

**Resource:** [cluster](../resources/cluster.md)
**Query cluster metrics**
**Operation ID:** `queryClusterMetrics`

Query cluster metrics by specified metric name and instance name, support instant and range query

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `query` | query | string | Yes | The promQL query string |
| `queryType` | query | metricsQueryType | Yes | The query type in the query, if use instant, the query will return the lastest instant value, if use range, the query will return a list of values in the time range |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterMetrics](../schemas/clusterMetrics/clusterMetrics.md)

