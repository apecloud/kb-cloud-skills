# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/jars

**Resource:** [clusterJar](../resources/clusterJar.md)
**Upload an immutable JAR version**
**Operation ID:** `uploadClusterJar`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | Doris or SelectDB engine of the target cluster. |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `Idempotency-Key` | header | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `kind` | [clusterJarKind](../schemas/clusterJarKind/clusterJarKind.md) | Yes |  |
| `file` | string (binary) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 413 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[clusterJarPackage](../schemas/clusterJarPackage/clusterJarPackage.md)

