# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/slow

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Query Loki slow logs**
**Operation ID:** `queryLokiSlowLogs`

Query slow logs through the Loki compatibility API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterExecutionLog](../schemas/clusterExecutionLog/clusterExecutionLog.md)

