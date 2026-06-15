# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/aggregate

**Resource:** [clusterLog](../resources/clusterLog.md)
**Aggregate cluster slow logs**
**Operation ID:** `aggregateSlowLogs`

Aggregate slow logs of a cluster (Victoria Logs backend only)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `startTime` | query | string | Yes | Start time in epoch nanoseconds. |
| `endTime` | query | string | Yes | End time in epoch nanoseconds. |
| `componentName` | query | string | No |  |
| `instanceName` | query | string | No |  |
| `query` | query | string | No |  |
| `limit` | query | string | No |  |
| `sortType` | query | sortType | No |  |
| `groupBy` | query | string | No |  |
| `topN` | query | integer (int32) | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterExecutionLogAggregateResponse](../schemas/clusterExecutionLogAggregateResponse/clusterExecutionLogAggregateResponse.md)

