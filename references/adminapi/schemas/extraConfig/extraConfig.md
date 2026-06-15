# extraConfig

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `title` | [internationalDesc](internationalDesc.md) | No |  |
| `type` | [configType](configType.md) | No |  |
| `defaultValue` | string | No |  |
| `isRequired` | boolean | No |  |
| `connectionCfgType` | [connectionCfgType](connectionCfgType.md) | No |  |
| `isDisplayOnlyCustomEndpoint` | boolean | No | Whether to display this config only when the endpoint type is custom. If true, it will not be displayed when the endpoint type is kubeblocks. |
| `displayWith` | string | No | The display condition of this config. If empty, it will always be displayed; otherwise, it will be displayed only when the config corresponding to displayWith (of boolean type) is true. |

