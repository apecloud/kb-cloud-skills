# paramTplApplyToClusterListItem

parameter template applicable to the cluster information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `count` | integer | Yes | The number of parameters in the parameter template |
| `name` | string | Yes | Name of parameter template. Name must be unique within an Org |
| `id` | string | No | id of parameter template |
| `needRestart` | boolean | Yes | whether to restart after applying this parameter template or not  |
| `partition` | string | Yes | the template partition |

