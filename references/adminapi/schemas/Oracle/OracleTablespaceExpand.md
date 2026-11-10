# OracleTablespaceExpand

One DDL operation per request. Use resize with fileId and sizeMB, or addFile with file. Shrinking and adding files to BIGFILE tablespaces are rejected.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | [OracleTablespaceExpandAction](OracleTablespaceExpandAction.md) | Yes |  |
| `fileId` | integer (int64) | No |  |
| `sizeMB` | integer (int64) | No |  |
| `file` | [OracleTablespaceFileSpec](OracleTablespaceFileSpec.md) | No |  |

