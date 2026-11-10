# OracleTablespaceCreate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Converted to uppercase. Limited to 30 ASCII bytes for compatibility with Oracle 12.1. |
| `contents` | [OracleTablespaceContents](OracleTablespaceContents.md) | No |  |
| `bigfile` | boolean | No |  |
| `files` | OracleTablespaceFileSpec[] | Yes | Exactly one file for BIGFILE tablespaces. |

