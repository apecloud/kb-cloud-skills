# environmentModuleDetails

Detailed information about a specific environment module, including its configuration, status and associated pods

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environmentName` | string | No | Name of the environment where the module is deployed |
| `moduleInfo` | [environmentModule](environmentModule.md) | No |  |
| `lastUpdated` | string (date-time) | No | Timestamp of when the module information was last updated |
| `modulePods` | pod[] | No | List of pods that belong to this environment module |

