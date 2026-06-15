# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/instances/metrics

**Resource:** [cluster](../resources/cluster.md)
**Get instaces metrics in cluster**
**Operation ID:** `getInstacesMetrics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[instanceMetricsList](../schemas/instanceMetricsList/instanceMetricsList.md)

