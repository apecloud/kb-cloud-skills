# disasterRecoveryStatusResponse

Status of the Disaster Recovery instance

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterId` | string | Yes | Unique identifier for the cluster |
| `clusterName` | string | No | Name of the cluster |
| `displayName` | string | No | User-friendly name of the cluster |
| `status` | string | No | Current operational status of the cluster |
| `parentId` | string | Yes | ID of the parent cluster, if applicable; can be empty if there is no parent relationship |
| `parentName` | string | No | Name of the parent cluster |
| `parentDisplayName` | string | No | User-friendly name of the parent cluster |
| `parentStatus` | string | No | Current operational status of the parent cluster |
| `delay` | number (double) | No | Delay time in seconds |
| `currentReplicationPoint` | string | No | Current replication point for the disaster recovery instance |

