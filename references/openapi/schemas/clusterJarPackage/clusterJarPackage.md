# clusterJarPackage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `name` | string | Yes |  |
| `kind` | [clusterJarKind](clusterJarKind.md) | Yes |  |
| `filename` | string | Yes |  |
| `sha256` | string | Yes |  |
| `size` | integer (int64) | Yes |  |
| `uri` | string | Yes |  |
| `published` | boolean | Yes |  |
| `archived` | boolean | Yes |  |
| `status` | string | Yes |  |
| `synced` | integer (int64) | Yes |  |
| `total` | integer (int64) | Yes |  |
| `createdBy` | string | Yes |  |
| `createdAt` | string (date-time) | Yes |  |
| `instances` | clusterJarReplica[] | Yes |  |

