# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/aggregate

**Resource:** [clusterLog](../resources/clusterLog.md)
**Aggregate cluster slow logs**
**Operation ID:** `aggregateSlowLogs`

Aggregate slow logs of a cluster over the full requested time range (Victoria Logs backend only). The result is not limited by the slow log list page size.

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
| `minExecutionTime` | query | number (double) | No | Minimum execution time in seconds. Decimal values are supported, for example 0.5. |
| `maxExecutionTime` | query | number (double) | No | Maximum execution time in seconds. Decimal values are supported, for example 0.5. |
| `minLockTime` | query | number (double) | No | Minimum lock time in seconds. Decimal values are supported, for example 0.001. |
| `maxLockTime` | query | number (double) | No | Maximum lock time in seconds. Decimal values are supported, for example 0.001. |
| `minRowsExamined` | query | integer (int64) | No |  |
| `maxRowsExamined` | query | integer (int64) | No |  |
| `minRowsSent` | query | integer (int64) | No |  |
| `maxRowsSent` | query | integer (int64) | No |  |
| `dbName` | query | string | No | Filter slow logs whose database name contains this value. |
| `userName` | query | string | No | Filter slow logs whose user name contains this value. |
| `clientIp` | query | string | No | Filter slow logs whose client IP contains this value, or is within this CIDR range when the value is valid CIDR. |
| `appName` | query | string | No | Filter slow logs whose application name contains this value. |
| `templateId` | query | string | No |  |
| `unclassifiedOnly` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterExecutionLogAggregateResponse](../schemas/clusterExecutionLogAggregateResponse/clusterExecutionLogAggregateResponse.md)

