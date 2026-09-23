# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/logs/loki/slow/stats

**Resource:** [clusterLokiLog](../resources/clusterLokiLog.md)
**Query Loki slow-log statistics**
**Operation ID:** `getLokiSlowLogStats`

Query slow-log statistics through the Loki compatibility API.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[clusterSlowLogStats](../schemas/clusterSlowLogStats/clusterSlowLogStats.md)

