# clusterAlertSummary

Cluster alert summary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `activeCount` | integer (int64) | No | number of active alerts after cluster/status/severity filters |
| `severityCounts` | object | No | active alert count grouped by severity |
| `topAlerts` | alertObject[] | No | top alerts for the cluster after filters |
| `updatedAt` | string (date-time) | No | response generation time |

