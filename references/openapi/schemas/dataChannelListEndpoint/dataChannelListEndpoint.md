# dataChannelListEndpoint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `name` | string | No |  |
| `engineName` | string | No |  |
| `endpointType` | [dataReplicationEndpointType](dataReplicationEndpointType.md) | No |  |
| `custom` | [customEndpoint](customEndpoint.md) | No |  |
| `kubeblocks` | [kubeblocksEndpoint](kubeblocksEndpoint.md) | No |  |
| `definition` | [definitionEndpoint](definitionEndpoint.md) | No |  |
| `channelNum` | integer | No | the number of channels associated with this endpoint |
| `description` | string | No |  |
| `status` | [endpointStatusEnum](endpointStatusEnum.md) | No |  |
| `extraCfgs` | object | No |  |

