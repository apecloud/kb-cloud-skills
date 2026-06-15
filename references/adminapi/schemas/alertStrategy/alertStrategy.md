# alertStrategy

Alert strategy information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `orgName` | string | No |  |
| `name` | string | No |  |
| `description` | string | No |  |
| `createdAt` | string (date-time) | No |  |
| `updatedAt` | string (date-time) | No |  |
| `receiverIds` | integer[] | Yes |  |
| `receivers` | alertReceiver[] | No |  |
| `envs` | string[] | No |  |
| `severities` | string[] | No |  |
| `rules` | string[] | No |  |
| `ruleObjs` | alterRuleRef[] | No |  |
| `engines` | string[] | No |  |
| `clusters` | string[] | No |  |
| `disabled` | boolean | No |  |
| `repeatInterval` | string | No |  |
| `muteTimeInterval` | object | No |  |

## Nested Fields

### `muteTimeInterval`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `weekdays` | integer[] | No |  |
| `times` | object | No |  |
| `onceMinutes` | integer | No | Only mute once for `onceMinutes` minutes |

#### `muteTimeInterval.times`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `startTime` | string | No | Mute start time, e.g. '17:00', should be in UTC time. |
| `endTime` | string | No | Mute end time, e.g. '24:00', should be in UTC time. |

