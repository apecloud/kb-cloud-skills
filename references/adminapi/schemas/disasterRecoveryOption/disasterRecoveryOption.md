# disasterRecoveryOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `instanceLimit` | integer | No |  |
| `settings` | [disasterRecoverySettings](disasterRecoverySettings.md) | No |  |
| `mode` | string | No | referenced cluster's mode, default is the primary cluster's mode |
| `status` | [engineOptionsDisasterRecoveryStatus](engineOptionsDisasterRecoveryStatus.md) | No |  |

