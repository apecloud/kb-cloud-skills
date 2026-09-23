# environmentModuleUpdate

Update information for an environment module

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Name of the environment module to update |
| `action` | [environmentModuleAction](environmentModuleAction.md) | Yes |  |
| `dryRun` | boolean | No | For a supported quick install or upgrade action, only run synchronous checks when true. When false or omitted, repeat the checks and submit the asynchronous task if all checks pass. |

