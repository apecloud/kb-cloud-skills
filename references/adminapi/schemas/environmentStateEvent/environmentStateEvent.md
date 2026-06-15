# environmentStateEvent

EventEnvironmentState contains details for the current and previous state of the environment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currentState` | string | Yes | The current state of the environment. |
| `prevState` | string | Yes | The previous state of the environment. |
| `reason` | string | Yes | The reason for the state transition. |
| `timestamp` | string (date-time) | Yes | The timestamp of the state transition. |
| `duration` | integer (int64) | No | The duration of the state in seconds. |

