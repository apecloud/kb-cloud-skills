# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/error

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Query Loki error logs**
**Operation ID:** `queryLokiErrorLogs`

Query error logs through the Loki compatibility API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterRawLogResponse](../schemas/clusterRawLogResponse/clusterRawLogResponse.md)

