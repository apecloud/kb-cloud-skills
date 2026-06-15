# parameterHistory

The history of a parameter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameterName` | string | Yes | The name of the parameter |
| `oldValue` | string | Yes | The old value of the parameter |
| `newValue` | string | Yes | The new value of the parameter |
| `updatedAt` | string (date-time) | Yes | The date and time the parameter was last updated |
| `source` | [eventSource](eventSource.md) | No |  |
| `operator` | string | No | operator of the event, if source is user, operator is user name; if source is system, operator is system name |
| `operatorId` | string | No | The user ID of the operator |
| `fileName` | string | No | The name of the configuration file |

