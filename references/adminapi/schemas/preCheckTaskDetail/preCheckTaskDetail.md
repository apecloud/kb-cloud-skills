# preCheckTaskDetail

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `taskID` | string | No |  |
| `taskStatus` | [preCheckStatus](preCheckStatus.md) | No |  |
| `progress` | integer (int32) | No |  |
| `checkers` | preCheckTaskItem[] | No |  |
| `errors` | preCheckResult[] | No |  |
| `warnings` | preCheckResult[] | No |  |
| `createdAt` | string (date-time) | No |  |
| `completedAt` | string (date-time) | No |  |

