# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/{jarId}/distribute

**Resource:** [clusterJar](../resources/clusterJar.md)
**Publish a JAR with optimistic manifest version checking**
**Operation ID:** `distributeClusterJar`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Doris or SelectDB engine of the target cluster. |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `jarId` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterJarPublish](../schemas/clusterJarPublish/clusterJarPublish.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

