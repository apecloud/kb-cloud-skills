# POST /admin/v1/environmentStaticClusters

**Resource:** [environment](../resources/environment.md)
**List reusable environment service clusters**
**Operation ID:** `listEnvironmentStaticClusters`

List retained MinIO, VictoriaMetrics, and VictoriaLogs clusters that can be explicitly attached when adding an environment. The optional engine filter restricts the results to one engine; omitted or empty returns all supported engines. Does not select a cluster.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [environmentStaticClusterList](../schemas/environmentStaticClusterList/environmentStaticClusterList.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[environmentObjectStorage](../schemas/environmentObjectStorage/environmentObjectStorage.md)

