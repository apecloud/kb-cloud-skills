# DailySLA

The SLA (Service Level Agreement) for a cluster on a specific date.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | No | The date for which the SLA is calculated, formatted as YYYY-MM-DD. |
| `sla` | number | No | The SLA value for the cluster on the specified date. Null indicates that the cluster was not existing on that date. |

