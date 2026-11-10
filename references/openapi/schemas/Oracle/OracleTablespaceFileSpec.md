# OracleTablespaceFileSpec

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Absolute database-server file path or ASM destination. Omit to use Oracle Managed Files (DB_CREATE_FILE_DEST must be configured). Existing files are never reused. |
| `sizeMB` | integer (int64) | Yes |  |
| `autoExtend` | boolean | No |  |
| `nextSizeMB` | integer (int64) | No | Required positive increment when autoExtend is true; otherwise omit. |
| `maxSizeMB` | integer (int64) | No | Maximum size when autoExtend is true; zero or omitted means UNLIMITED. Otherwise omit. |

