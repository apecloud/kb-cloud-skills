# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/export

**Resource:** [clusterLog](../resources/clusterLog.md)
**Export cluster logs**
**Operation ID:** `exportClusterLogs`

Export cluster logs and return as a file download

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `logType` | query | string | Yes | Log type: runninglog, errorlog, slow, auditlog |
| `startTime` | query | integer (int64) | No | Start time in epoch nanoseconds. If omitted, exports from the earliest available log |
| `endTime` | query | integer (int64) | No | End time in epoch nanoseconds. If omitted, exports up to the latest available log |
| `format` | query | string | No | Export format: csv, raw, jsonl |
| `query` | query | string | No | Optional search query |
| `filename` | query | string | No | Optional log filename filter |
| `componentName` | query | string | No | Optional component name filter |
| `instanceName` | query | string | No | Optional instance name filter |
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
| `maxLines` | query | integer (int64) | No | Maximum number of lines to export. Defaults to 100000 if omitted |

## Responses

| Status | Description |
|--------|-------------|
| 200 | File download |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

