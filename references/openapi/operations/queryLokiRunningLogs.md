# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/running

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Query Loki running logs**
**Operation ID:** `queryLokiRunningLogs`

Query running logs through the Loki compatibility API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterRawLogResponse](../schemas/clusterRawLogResponse/clusterRawLogResponse.md)

