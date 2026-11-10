# OracleTablespace

Oracle tablespace in the datasource connection's current container. Sizes are in MiB. Supports Oracle 12c and 19c.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `contents` | string | Yes | PERMANENT, TEMPORARY, or UNDO. |
| `status` | string | Yes |  |
| `bigfile` | boolean | Yes |  |
| `blockSize` | integer (int64) | Yes |  |
| `containerName` | string | Yes |  |
| `isDefault` | boolean | Yes | Whether this is a default permanent or temporary tablespace, including default temporary group members. |
| `allocatedSizeMB` | number (double) | Yes |  |
| `usedSizeMB` | number (double) | Yes | Allocated file space minus free extents, or temporary file space currently allocated to temporary segments. |
| `maxSizeMB` | number (double) | Yes | Configured file growth limit; does not imply available disk capacity. |
| `files` | OracleTablespaceFile[] | Yes |  |

