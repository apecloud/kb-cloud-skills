# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/pod

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Query Loki pod logs**
**Operation ID:** `queryLokiPodLogs`

Query pod logs through the Loki compatibility API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterRawLogResponse](../schemas/clusterRawLogResponse/clusterRawLogResponse.md)

