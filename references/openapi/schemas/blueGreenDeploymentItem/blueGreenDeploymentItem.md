# blueGreenDeploymentItem

blueGreenDeploymentItem is the response to a blue-green deployment creation request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deploymentID` | string | Yes | The ID of the blue-green deployment. |
| `deploymentName` | string | No | The name of the blue-green deployment. |
| `blueCluster` | [clusterListItem](clusterListItem.md) | No |  |
| `greenCluster` | [clusterListItem](clusterListItem.md) | No |  |
| `deploymentStatus` | [blueGreenDeploymentStatus](blueGreenDeploymentStatus.md) | No |  |
| `replicationLag` | string | No | The lag of the replication. |
| `createdAt` | string (date-time) | No | The creation time of the blue-green deployment. |
| `updatedAt` | string (date-time) | No | The update time of the blue-green deployment. |

