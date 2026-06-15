# DmsViewMetadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `viewName` | string | No | The name of the view |
| `database` | string | No | The database in which the view will be created |
| `replace` | boolean | No | Whether to replace the existing view if it exists |
| `definer` | string | No | The definer of the view |
| `sqlSecurity` | string | No | The SQL security context of the view (e.g., DEFINER or INVOKER) |
| `checkOption` | string | No | The WITH CHECK OPTION clause (e.g., CASCADED or LOCAL) |
| `algorithm` | string | No | The algorithm used for the view (e.g., UNDEFINED, MERGE, TEMPTABLE) |
| `definition` | string | No | The SQL statement defining the view |

