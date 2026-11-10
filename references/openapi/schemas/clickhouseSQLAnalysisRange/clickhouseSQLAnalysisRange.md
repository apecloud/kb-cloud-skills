# clickhouseSQLAnalysisRange

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | No | Requested range label (1h, 6h, 24h, 7d). |
| `start` | string | No | Range start in RFC3339 UTC. |
| `end` | string | No | Range end in RFC3339 UTC. |
| `durationSeconds` | integer (int64) | No | Range duration in seconds. |

