# taskStep

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `stepId` | string | Yes | Unique identifier for the step |
| `stepName` | string | Yes | Name of the step |
| `methodName` | string | Yes | Method to be executed in this step |
| `inputs` | object | No | Input parameters for the step |
| `outputs` | object | No | Output parameters from the step |
| `retryLimit` | integer | No | Number of times to retry the step in case of failure |
| `currRetryCount` | integer | No | Current retry count for the step |
| `timeoutSecond` | integer | No | Timeout duration for the step in seconds |
| `status` | [taskStatus](taskStatus.md) | Yes |  |
| `message` | string | No | Detailed message about the step status |
| `createdAt` | string (date-time) | Yes | Timestamp when the step was created |
| `updatedAt` | string (date-time) | Yes | Timestamp when the step was last updated |
| `startedAt` | string (date-time) | No | Timestamp when the task was deleted |
| `completionTime` | string (date-time) | No | Time when the task completed or failed |
| `detail` | object | No | Detailed information about the step |

