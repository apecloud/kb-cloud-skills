# backupStatsType

Totalsize and number of backups for the backup type

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | backup type |
| `size` | string | No | totalsize of backups for each engine, A string with capacity units in the form of "1Gi", "1Mi", "1Ki". |
| `num` | integer (int64) | No | The number of backups for each engine |

