# parameterTemplate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | name of default parameter template |
| `description` | [localizedDescription](localizedDescription.md) | Yes |  |
| `majorVersion` | string | No | match the major version set in the component |
| `majorVersions` | string[] | No | match the major versions set in the component, such as 8.0, 8.1, 8.2 |
| `refs` | ref[] | Yes | refs contains the references to the configuration templates |
| `defaultUse` | boolean | Yes | whether the default parameter template is used by default, set in componentDefinition.configs, only one default parameter template can be set in certain family. |

