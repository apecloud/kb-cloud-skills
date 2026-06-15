# endpoint

Endpoint is the information of cluster endpoints

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | string | Yes | title of the endpoint |
| `component` | string | Yes | Component type name |
| `hosts` | string[] | Yes | Endpoint hosts |
| `port` | integer (int32) | Yes | Endpoint port |
| `type` | [endpointType](endpointType.md) | Yes |  |
| `networkType` | [endpointNetworkType](endpointNetworkType.md) | Yes |  |
| `serviceName` | string | Yes | Service name of endpoint |
| `podService` | boolean | No | Pod service name of endpoint |
| `portName` | string | Yes | Port name of endpoint |
| `instances` | string[] | No | Endpoint backend instances |
| `mutable` | boolean | Yes | Whether the endpoint is mutable |

