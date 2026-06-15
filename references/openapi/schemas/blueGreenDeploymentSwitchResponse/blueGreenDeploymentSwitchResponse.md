# blueGreenDeploymentSwitchResponse

blueGreenDeploymentSwitchResponse represents the response when switching a blue-green deployment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deploymentID` | string | No | The ID of the blue-green deployment. |
| `taskId` | string | Yes | Task ID. |
| `taskStatus` | [taskStatus](taskStatus.md) | No |  |
| `steps` | blueGreenDeploymentSwitchStep[] | No | The steps involved in the blue-green deployment switch. |

