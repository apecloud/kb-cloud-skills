# endpointOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | [localizedDescription](localizedDescription.md) | Yes |  |
| `component` | string | Yes |  |
| `portName` | string | Yes |  |
| `port` | integer (int32) | Yes |  |
| `protocol` | string | Yes |  |
| `targetPort` | string | Yes |  |
| `type` | string[] | Yes |  |
| `supportsSystemUse` | boolean | No | whether the endpoint supports system use, such as health check, dms, databases & accounts management etc. |
| `supportsReadonly` | boolean | No | whether the engine supports readonly endpoint |
| `servicePattern` | [engineOptionsServicePattern](engineOptionsServicePattern.md) | No |  |
| `serviceNameRegex` | string | No | ServiceName regular expression |
| `serviceName` | string | No | service suffix, defined in ComponentDefinition |
| `selector` | object | No | selector of k8s service |
| `disasterRecoverySelector` | object | No | selector of k8s service |
| `followNetworkMode` | boolean | No | whether the endpoint follows the network mode of the component |
| `compatibleKBVersion` | string | No | compatible KubeBlocks Major versions |

