# environmentStatusHistoryDay

Daily status history for the environment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date` | string | Yes | The date of this day's status history. |
| `status` | string | Yes | The primary status for this day based on priority. |
| `statusDuration` | object | Yes | Duration in seconds for each status on this day. |
| `statusHistory` | environmentStateEvent[] | Yes | List of state transition events that occurred on this day. |
| `inherited` | boolean | Yes | Indicates if the status was inherited from the previous day. |

