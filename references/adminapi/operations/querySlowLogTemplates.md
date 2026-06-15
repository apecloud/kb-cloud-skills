# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/slow/templates

**Resource:** [clusterLog](../resources/clusterLog.md)
**Query cluster slow log templates**
**Operation ID:** `querySlowLogTemplates`

Query slow log templates of a cluster (VictoriaLogs backend only)

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
| `topN` | query | integer (int32) | No |  |
| `sortBy` | query | string | No | Sort templates by count or avgExecutionTime. |
| `sortType` | query | sortType | No |  |
| `minExecutionTime` | query | number (double) | No | Minimum execution time in seconds. Decimal values are supported, for example 0.5. |
| `maxExecutionTime` | query | number (double) | No | Maximum execution time in seconds. Decimal values are supported, for example 0.5. |
| `minLockTime` | query | number (double) | No | Minimum lock time in seconds. Decimal values are supported, for example 0.001. |
| `maxLockTime` | query | number (double) | No | Maximum lock time in seconds. Decimal values are supported, for example 0.001. |
| `minRowsExamined` | query | integer (int64) | No |  |
| `maxRowsExamined` | query | integer (int64) | No |  |
| `minRowsSent` | query | integer (int64) | No |  |
| `maxRowsSent` | query | integer (int64) | No |  |
| `dbName` | query | string | No |  |
| `dbNameContains` | query | string | No |  |
| `userName` | query | string | No |  |
| `userNameContains` | query | string | No |  |
| `clientIp` | query | string | No |  |
| `clientIpContains` | query | string | No |  |
| `clientIpCIDR` | query | string | No |  |
| `appName` | query | string | No |  |
| `appNameContains` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterSlowLogTemplateList](../schemas/clusterSlowLogTemplateList/clusterSlowLogTemplateList.md)

