# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/hits

**Resource:** [clusterLog](../resources/clusterLog.md)
**Query log hits histogram**
**Operation ID:** `queryLogHits`

Query log hits histogram for time-bucketed log counts (VictoriaLogs only)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `startTime` | query | string | Yes | Start time in epoch nanoseconds. |
| `endTime` | query | string | Yes | End time in epoch nanoseconds. |
| `step` | query | string | Yes | Time bucket size, e.g. 5s, 30s, 1m, 5m, 30m, 1h |
| `logType` | query | string | Yes | Log type: runninglog, errorlog, slow, auditlog |
| `componentName` | query | string | No |  |
| `instanceName` | query | string | No |  |
| `query` | query | string | No |  |
| `minExecutionTime` | query | number (double) | No | Minimum slow log execution time in seconds. Only applies when logType=slow. |
| `maxExecutionTime` | query | number (double) | No | Maximum slow log execution time in seconds. Only applies when logType=slow. |
| `minLockTime` | query | number (double) | No | Minimum slow log lock time in seconds. Only applies when logType=slow. |
| `maxLockTime` | query | number (double) | No | Maximum slow log lock time in seconds. Only applies when logType=slow. |
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
| `templateId` | query | string | No |  |
| `unclassifiedOnly` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterLogHitsResponse](../schemas/clusterLogHitsResponse/clusterLogHitsResponse.md)

