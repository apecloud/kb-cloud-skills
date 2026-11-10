# dataChannelEndpointCreate

Use endpointType custom or kubeblocks with the corresponding inline connection configuration, or endpointType definition with definition.endpointID to reuse an existing data endpoint. Inline connection configuration is not used for endpointType definition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `engineName` | string | No |  |
| `definitionName` | string | No |  |
| `endpointType` | [dataReplicationEndpointType](dataReplicationEndpointType.md) | No |  |
| `custom` | [customEndpointCreate](customEndpointCreate.md) | No |  |
| `kubeblocks` | [kubeblocksEndpoint](kubeblocksEndpoint.md) | No |  |
| `definition` | [definitionEndpoint](definitionEndpoint.md) | No |  |
| `description` | string | No |  |
| `extraCfgs` | object | No |  |

