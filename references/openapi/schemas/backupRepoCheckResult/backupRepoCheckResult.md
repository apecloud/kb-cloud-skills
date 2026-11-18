# backupRepoCheckResult

Result of the platform storage access check, independent of the BackupRepo CR phase.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | [backupRepoCheckStatus](backupRepoCheckStatus.md) | Yes |  |
| `message` | string | No |  |
| `checkedAt` | string (date-time) | No |  |

