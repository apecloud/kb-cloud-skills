# postgresqlSpaceSummary

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databaseName` | string | No |  |
| `databaseSizeBytes` | integer (int64) | No |  |
| `tableCount` | integer (int64) | Yes |  |
| `indexCount` | integer (int64) | Yes |  |
| `toastRelationCount` | integer (int64) | Yes |  |
| `largestTableBytes` | integer (int64) | No |  |
| `largestIndexBytes` | integer (int64) | No |  |
| `tableListTruncated` | boolean | Yes |  |
| `indexListTruncated` | boolean | Yes |  |

