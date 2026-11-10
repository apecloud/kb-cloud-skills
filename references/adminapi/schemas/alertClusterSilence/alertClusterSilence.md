# alertClusterSilence

Pause notifications while continuing to record alerts. Set enabled to false to cancel. Time windows include their start and exclude their end.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `rules` | string[] | No | Alert names to silence. Empty or omitted means all alerts for the resource. |
| `mode` | [alertClusterSilenceMode](alertClusterSilenceMode.md) | No |  |
| `startsAt` | string (date-time) | No | Required for once. Absolute start of the silence window. |
| `endsAt` | string (date-time) | No | Required for once. Must be later than startsAt. |
| `weekdays` | integer[] | No | Required for weekly. Sunday is 0. Overnight windows belong to the weekday on which they start. |
| `startTime` | string | No | Required for weekly, in HH:mm format. |
| `endTime` | string | No | Required for weekly, in HH:mm format. Earlier than startTime means the following day; equal times are invalid. |
| `timeZone` | string | No | Required for weekly. IANA timezone, e.g. Asia/Shanghai or UTC. |

