# dataEndpointCreate

Connection configuration for an independently managed data endpoint.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No |  |
| `engineName` | string | No |  |
| `definitionName` | string | No |  |
| `endpointType` | [dataEndpointTypeCreation](dataEndpointTypeCreation.md) | No |  |
| `custom` | [customEndpointCreate](customEndpointCreate.md) | No |  |
| `kubeblocks` | [kubeblocksEndpoint](kubeblocksEndpoint.md) | No |  |
| `description` | string | No |  |
| `extraCfgs` | object | No |  |

