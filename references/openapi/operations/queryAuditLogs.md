# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/audit

**Resource:** [clusterLog](../resources/clusterLog.md)
**Query cluster audit logs**
**Operation ID:** `queryAuditLogs`

Query audit logs of a cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `startTime` | query | string | Yes | Start time in epoch nanoseconds. |
| `endTime` | query | string | Yes | End time in epoch nanoseconds. |
| `limit` | query | string | No |  |
| `componentName` | query | string | No |  |
| `instanceName` | query | string | No |  |
| `sortType` | query | sortType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterExecutionLog](../schemas/clusterExecutionLog/clusterExecutionLog.md)

