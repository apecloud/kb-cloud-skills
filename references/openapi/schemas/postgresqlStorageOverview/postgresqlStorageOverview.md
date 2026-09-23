# postgresqlStorageOverview

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `source` | string | Yes |  |
| `instances` | postgresqlStorageInstanceUsage[] | Yes | Physical PostgreSQL replica storage usage split by pod/PVC/role. |

