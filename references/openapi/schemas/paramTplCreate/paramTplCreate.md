# paramTplCreate

parameter template create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | Description of parameter template |
| `name` | string | Yes | Name of parameter template. Name must be unique within an Org |
| `oriName` | string | Yes | Name of the original parameter template. |
| `oriPartition` | [parameterTemplatePartition](parameterTemplatePartition.md) | Yes |  |
| `isPrivate` | boolean | No | Determines whether the user can see this parameter template |

