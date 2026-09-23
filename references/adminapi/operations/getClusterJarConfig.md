# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars/config

**Resource:** [clusterJar](../resources/clusterJar.md)
**Get external JAR capability and configuration**
**Operation ID:** `getClusterJarConfig`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Doris or SelectDB engine of the target cluster. |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

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

**Success Response Schema:**

[clusterJarConfig](../schemas/clusterJarConfig/clusterJarConfig.md)

