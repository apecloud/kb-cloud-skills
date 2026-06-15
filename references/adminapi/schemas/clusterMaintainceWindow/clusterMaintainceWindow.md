# clusterMaintainceWindow

the maintenance window for a cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `startHour` | integer | No | start hour, must be 0-23, use UTC timezone |
| `endHour` | integer | No | end hour, must be 0-23 and greater than start hour, use UTC timezone |
| `weekdays` | string | No | weekdays, comma separated values of 1-7 |

