# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/export

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Export Loki logs**
**Operation ID:** `exportLokiClusterLogs`

Export logs through the Loki compatibility API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `logType` | query | string | Yes | Log type: runninglog, errorlog, slow, auditlog |
| `startTime` | query | integer (int64) | No | Start time in epoch nanoseconds. If omitted, exports from the earliest available log |
| `endTime` | query | integer (int64) | No | End time in epoch nanoseconds. If omitted, exports up to the latest available log |
| `format` | query | string | No | Export format: csv, raw, jsonl |
| `maxLines` | query | integer (int64) | No | Maximum number of lines to export. Defaults to 100000 if omitted |

## Responses

| Status | Description |
|--------|-------------|
| 200 | File download |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

