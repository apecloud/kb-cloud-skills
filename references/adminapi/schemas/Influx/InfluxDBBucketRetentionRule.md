# InfluxDBBucketRetentionRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [InfluxDBRetentionRuleType](InfluxDBRetentionRuleType.md) | No |  |
| `everySeconds` | integer (int64) | No | 0 means forever. Positive retention must be at least 3600 seconds. Omit on PATCH to preserve retention. |
| `shardGroupDurationSeconds` | integer (int64) | No | 0 selects the native default. Omit on PATCH to preserve the existing duration. |

