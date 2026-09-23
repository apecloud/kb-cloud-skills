# POST /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/archive

**Resource:** [clusterJar](../resources/clusterJar.md)
**Archive a JAR while retaining published files and startup synchronization**
**Operation ID:** `archiveClusterJar`

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
| 204 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

