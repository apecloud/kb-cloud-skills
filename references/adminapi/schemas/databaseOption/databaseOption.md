# databaseOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |
| `update` | boolean | No |  |
| `maxLen` | integer (int32) | No | max length of database name.
If not set, use default value.
 |
| `minLen` | integer (int32) | No | min length of database name.
If not set, use default value.
 |
| `databaseNamePattern` | string | No |  |
| `patternDescription` | object | No |  |
| `listOption` | string[] | No | The database option information that will be displayed when listing databases
 |
| `protectedDatabases` | string[] | No | Database names that should be visible in database lists but protected from destructive operations.
 |
| `availableOptions` | string[] | No | The database option cloud be set when creating databases
 |
| `availbaleUpdateOptions` | object[] | No | The database option name and type cloud be updated when updating databases
 |

## Nested Fields

### `patternDescription`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `zh-CN` | string | No |  |
| `en-US` | string | No |  |

### `availbaleUpdateOptions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `type` | string | No |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |

