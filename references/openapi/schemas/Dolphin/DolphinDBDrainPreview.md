# DolphinDBDrainPreview

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `observedAt` | string (date-time) | Yes |  |
| `source` | string | Yes |  |
| `remainingNodes` | string[] | Yes |  |
| `total` | integer | Yes |  |
| `offset` | integer | Yes |  |
| `entries` | DolphinDBDrainMigration[] | Yes |  |
| `capacityCheck` | string | Yes | Always notValidated. This preview is not proof of sufficient physical capacity or permission to delete the node. |

