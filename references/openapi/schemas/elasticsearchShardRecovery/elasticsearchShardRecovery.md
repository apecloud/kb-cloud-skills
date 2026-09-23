# elasticsearchShardRecovery

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `index` | string | No |  |
| `shard` | integer (int64) | No |  |
| `type` | string | No |  |
| `stage` | string | No |  |
| `primary` | boolean | No |  |
| `startTimeMillis` | integer (int64) | No |  |
| `totalTimeMillis` | integer (int64) | No |  |
| `source` | [elasticsearchShardNode](elasticsearchShardNode.md) | No |  |
| `target` | [elasticsearchShardNode](elasticsearchShardNode.md) | No |  |
| `translog` | [elasticsearchRecoveryTranslog](elasticsearchRecoveryTranslog.md) | No |  |
| `size` | [elasticsearchRecoverySize](elasticsearchRecoverySize.md) | No |  |

