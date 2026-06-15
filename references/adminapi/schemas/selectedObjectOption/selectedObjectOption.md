# selectedObjectOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tree` | object | No |  |
| `convertToParameters` | object[] | No | Parameters for specifying which objects to include in the selective backup |

## Nested Fields

### `tree`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `switchWithDatabase` | boolean | No | if set to true, the tree will switch when database is switched. This is used for database-level backup, and the root level of the tree is database. If not set or set to false, the tree will not switch when database is switched, and the root level of the tree is instance. |
| `sql` | string | Yes | The SQL query to retrieve the object tree |
| `levelOrder` | object[] | Yes | The order of object types in the hierarchy |

#### `tree.levelOrder`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | The object type, e.g., "database", "schema", "table" |
| `columnName` | string | No | The column name of the object type which is defined in the sql, e.g., "database_name", "schema_name", "table_name" |
| `typeFromColumn` | string | No | The object type which is defined in the sql, mutually exclusive with `type` |

### `convertToParameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameterName` | string | Yes | The name of the parameter for selective backup, e.g., "tables" |
| `valueTemplate` | string | Yes | The format of the value with the tree level index, e.g., "{0}", "{0}.{1}" |
| `skipWhenParentLevelsSelectedAll` | boolean | No | Whether to skip the current level when all of the parent level is selected all |
| `levelIndex` | integer | No | The index of the current level in the tree level order |

