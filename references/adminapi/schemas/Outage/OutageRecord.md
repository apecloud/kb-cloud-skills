# OutageRecord

Records the outage events of a cluster for SLA calculation. It is designed to ensure that for any given cluster, there can be at most one active outage record at any time.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The unique identifier for the outage record. |
| `clusterID` | string | Yes | The id of cluster. |
| `outageStartTime` | integer (int64) | No | The Unix timestamp (in seconds) when the outage began (UTC). |
| `outageEndTime` | integer (int64) | No | The Unix timestamp (in seconds) when the outage was resolved (UTC). A null value indicates that the outage is still ongoing. |
| `lastFailureReason` | string | No | The error message from the last failed probe. |
| `failureCount` | integer (int32) | No | The number of consecutive failures in this outage event. |
| `createdAt` | string (date-time) | No | The timestamp when the record was created. |
| `updatedAt` | string (date-time) | No | The timestamp when the record was last updated. |

