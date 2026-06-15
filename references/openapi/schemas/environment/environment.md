# environment

Environment info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `provider` | string | Yes | Provider |
| `region` | string | Yes | Region |
| `availabilityZones` | string[] | Yes | Availability Zones |
| `networkConfig` | [networkConfig](networkConfig.md) | No |  |
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `description` | string | No | The description of the organization |
| `displayName` | string | No | The display name of the context |
| `id` | string (uuid) | Yes | environment id |
| `name` | string | Yes | The full, unique name of this Object in the format contexts/{name}, set during creation. name must be a valid RFC 1123 compliant DNS label |
| `orgName` | string | Yes | Organization Name |
| `state` | [environmentState](environmentState.md) | Yes |  |
| `type` | [environmentType](environmentType.md) | Yes |  |
| `updatedAt` | string (date-time) | Yes | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC. Populated by the system. Read-only. Null for lists |
| `imageRegistry` | string | No | Image registry URL used by the environment. Must match image_registries.url, not image_registries.name. |
| `extraInfo` | string | No | extra info for environment |
| `kbVersion` | string | No | KubeBlocks version of the environment |
| `namespaces` | string[] | No | namespace info for environment |
| `defaultStorageClass` | string | Yes | the default storageClass for the environment |
| `clusterValidationPolicy` | [clusterValidationPolicy](clusterValidationPolicy.md) | No |  |
| `architecture` | [environmentArchitecture](environmentArchitecture.md) | No |  |

