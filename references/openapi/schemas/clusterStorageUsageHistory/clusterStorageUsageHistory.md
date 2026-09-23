# clusterStorageUsageHistory

Per-instance cluster storage usage history collected from backend-owned fixed metrics.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `timeRange` | string | Yes | Requested history range. Supported values are 24h and 7d. |
| `start` | string | Yes | History query start timestamp in UTC. |
| `end` | string | Yes | History query end timestamp in UTC. |
| `instances` | clusterStorageUsageHistoryInstance[] | Yes |  |
| `source` | string | Yes | Metrics source used to build the history. |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. |

