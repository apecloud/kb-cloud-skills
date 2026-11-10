# InfluxDBBucketUpdate

Partial update. Omitted fields are unchanged; empty description clears it. Absent or empty retentionRules does not change retention. To retain forever send everySeconds: 0. System buckets cannot be renamed.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `description` | string | No |  |
| `retentionRules` | InfluxDBBucketRetentionRule[] | No |  |

