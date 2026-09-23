# performanceTrends

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `range` | [performanceTrendRange](performanceTrendRange.md) | Yes |  |
| `granularity` | string | Yes | Controlled backend query step. |
| `summary` | performanceTrendSummary[] | Yes | Per-series numeric summary. changeDirection is present only when at least two points exist. |
| `series` | performanceTrendSeries[] | Yes | Successfully collected and displayable metric series only. Unsupported, empty, or failed metrics are not represented as per-metric entries. |
| `sources` | performanceTrendSource[] | Yes | Coarse collection source status. Messages are sanitized and do not expose PromQL, endpoints, credentials, or raw internal errors. |
| `warnings` | string[] | Yes |  |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. |

