# DolphinDBDrainMigration

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `chunkId` | string | Yes |  |
| `srcNode` | string | Yes |  |
| `destNode` | string | Yes | Empty for a redundant replica deletion. |
| `action` | string | Yes | moveReplica or dropRedundantReplica. Preview does not execute either action. |

