# GET /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/download

**Resource:** [clusterJar](../resources/clusterJar.md)
**Download the original JAR**
**Operation ID:** `downloadClusterJar`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Doris or SelectDB engine of the target cluster. |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `jarId` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

