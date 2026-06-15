# environment

Environment info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `provider` | string | Yes | Cloud Provider |
| `region` | string | Yes | Cloud Region |
| `availabilityZones` | string[] | Yes | Availability Zones |
| `schedulingConfig` | [schedulingConfig](schedulingConfig.md) | No |  |
| `networkConfig` | [networkConfig](networkConfig.md) | No |  |
| `description` | string | No | The description of the organization |
| `displayName` | string | Yes | The display name of the context |
| `id` | string (uuid) | Yes |  |
| `name` | string | Yes | The full, unique name of this Object in the format contexts/{name}, set during creation. name must be a valid RFC 1123 compliant DNS label |
| `organizations` | string[] | Yes | Organizations that have access for this environment |
| `metricsMonitorEnabled` | boolean | No | The native VM cluster is deployed in environment or not. |
| `state` | [environmentState](environmentState.md) | Yes |  |
| `type` | [environmentType](environmentType.md) | Yes |  |
| `provisionConfig` | [provisionConfig](provisionConfig.md) | Yes |  |
| `autohealingConfig` | [autohealingConfig](autohealingConfig.md) | No |  |
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `extraInfo` | string | No | Extra info for environment |
| `deletePolicy` | [environmentDeletePolicy](environmentDeletePolicy.md) | No |  |
| `clusterValidationPolicy` | [clusterValidationPolicy](clusterValidationPolicy.md) | No |  |
| `architecture` | [environmentArchitecture](environmentArchitecture.md) | No |  |
| `dns` | [dns](dns.md) | No |  |
| `slaEnabled` | boolean | No | whether to enable calculate the cluster SLA for the environment |

