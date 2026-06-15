# blueGreenDeploymentPreCheckResponse

blueGreenDeploymentPreCheckResponse is the response for retrieving the precheck task of a blue-green deployment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskId` | string | Yes | Task ID. |
| `taskStatus` | [taskStatus](taskStatus.md) | No |  |
| `checkers` | blueGreenDeploymentPrecheckItem[] | No | The checkers of the precheck task. |

