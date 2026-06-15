# paramTplUpdate

paramTplUpdate is the payload to update a parameter template

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `specName` | string | No | Specify parameters belongs to which spec. Currently, only one configuration file corresponds to a specName, so the configuration file name is omitted. |
| `parameters` | object | No | Specify parameters list to be updated |
| `newParamTplName` | string | No | Specify the new name of the parameter template |
| `description` | string | No | The description of the parameter template |
| `rawContent` | string | No | The raw content of the configuration file |

