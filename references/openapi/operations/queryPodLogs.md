# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/pod

**Resource:** [clusterLog](../resources/clusterLog.md)
**Query cluster pod logs**
**Operation ID:** `queryPodLogs`

Query pod logs of a cluster

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `componentName` | query | string | No |  |
| `instanceName` | query | string | No |  |
| `filename` | query | string | No |  |
| `startTime` | query | string | Yes | Start time in epoch nanoseconds. |
| `endTime` | query | string | Yes | End time in epoch nanoseconds. |
| `limit` | query | string | No |  |
| `sortType` | query | sortType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterRawLogResponse](../schemas/clusterRawLogResponse/clusterRawLogResponse.md)

