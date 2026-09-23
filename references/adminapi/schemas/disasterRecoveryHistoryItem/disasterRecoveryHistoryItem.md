# disasterRecoveryHistoryItem

DisasterRecovery history detail for Cluster

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskID` | string | No | the ID of disaster recovery task in TaskFlow |
| `parentClusterID` | string | No | the ID of parent cluster |
| `parentClusterName` | string | No | the Name of parent cluster |
| `parentEnvName` | string | No | parent env name |
| `clusterID` | string | No | the ID of promote cluster |
| `clusterName` | string | No | the Name of promote cluster |
| `envName` | string | No | env name |
| `eventType` | [disasterRecoveryEventType](disasterRecoveryEventType.md) | No |  |
| `reason` | string | No | the reason of promote |
| `operator` | string | No | the operator name |
| `operatorId` | string | No | the user ID of the operator |
| `createdAt` | string (date-time) | No | the create time of promote event |
| `updateAt` | string (date-time) | No | the update time of promote event |
| `status` | [disasterRecoveryStatus](disasterRecoveryStatus.md) | No |  |

