# environmentUpdate

Environment info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the organization |
| `displayName` | string | No | The display name of the context |
| `type` | [environmentType](environmentType.md) | No |  |
| `organizations` | string[] | No | Organizations that have access for this environment |
| `namespaces` | string[] | No | Organizations that have access for this environment |
| `cpuOverCommitRatio` | number (double) | No | the over commit ratio of cpu |
| `memoryOverCommitRatio` | number (double) | No | the over commit ratio of memory |
| `autohealingConfig` | [autohealingConfig](autohealingConfig.md) | No |  |
| `defaultStorageClass` | string | No | the default storage class of this environment |
| `imageRegistry` | string | No | Image registry URL used to pull images. Must match image_registries.url, not image_registries.name. |
| `nodePortEnabled` | boolean | No | Enable node port service for this environment |
| `lbEnabled` | boolean | No | Enable load balancer service for this environment |
| `domainEnabled` | boolean | No | Enable domain service for this environment |
| `internetLBEnabled` | boolean | No | Enable the Internet load balancer service for this environment |
| `networkModes` | networkMode[] | No | Network modes of the environment |
| `deletePolicy` | [environmentDeletePolicy](environmentDeletePolicy.md) | No |  |
| `clusterValidationPolicy` | [clusterValidationPolicy](clusterValidationPolicy.md) | No |  |
| `provider` | string | No | Cloud Provider |
| `slaEnabled` | boolean | No | whether to enable calculate the cluster SLA for the environment |
| `koordinatorEnabled` | boolean | No | Whether this environment has Koordinator installed and can use Koordinator scheduler and reservations. |
| `ipPoolProviders` | ipPoolProvider[] | No | KBE Pod IP pool providers enabled for discovery and explicit pool selection. An empty array disables this capability. |
| `clusterSchedulingPolicy` | [clusterSchedulingPolicy](clusterSchedulingPolicy.md) | No |  |
| `additionalTopologyKeys` | string[] | No | Additional Kubernetes topology label keys used by subsequently created or re-rendered clusters; existing Pods are not migrated automatically. Omit or use null to preserve the current value; use an empty array to clear all additional keys. Values must be valid Kubernetes qualified label keys. Infrastructure integrations or administrators must label all eligible nodes consistently; missing labels can cause unintended scheduling behavior and undermine failure-domain isolation. Too few eligible topology domains can leave Pods Pending under hard anti-affinity. If the Kubernetes LimitPodHardAntiAffinityTopology admission plugin is enabled, Pod creation is rejected for required anti-affinity using topology keys other than kubernetes.io/hostname, which can prevent the database cluster from becoming ready. |

