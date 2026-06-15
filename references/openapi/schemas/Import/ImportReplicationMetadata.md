# ImportReplicationMetadata

Replication metadata tree definition for import object selection.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metadataType` | string | Yes | Metadata node type identifier (e.g. database, table). |
| `children` | ImportReplicationMetadata[] | No | Child metadata nodes. |

