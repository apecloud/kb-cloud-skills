# Partition

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int32) | Yes |  |
| `leader` | [brokerNode](brokerNode.md) | Yes |  |
| `replicas` | brokerNode[] | No |  |
| `isr` | brokerNode[] | No | In-Sync Replicas |
| `beginningOffset` | integer (int64) | No |  |
| `endOffset` | integer (int64) | No |  |

