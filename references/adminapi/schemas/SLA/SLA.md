# SLA

The SLA (Service Level Agreement) for a cluster.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cluster` | [SLACluster](SLACluster.md) | No |  |
| `detail` | [OutageRecordList](OutageRecordList.md) | No |  |
| `sla` | number | No | The SLA value for the cluster. |
| `targetThreshold` | number | No | The target SLA threshold value for the cluster. |
| `totalDuration` | integer (int64) | No | The total duration of the outage records. |
| `totalDowntime` | integer (int64) | No | The total downtime duration of the outage records. |

