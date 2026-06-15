# environmentStatusHistory

Environment status history with SLA calculation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sla` | string | Yes | The SLA percentage (availability) for the environment. |
| `days` | environmentStatusHistoryDay[] | Yes | Daily status history data. |
| `statusDuration` | object | Yes | Total duration in seconds for each status across all days. |

