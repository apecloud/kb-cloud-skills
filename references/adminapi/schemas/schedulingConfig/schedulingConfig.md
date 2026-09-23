# schedulingConfig

Configuration of resource scheduling for this environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterSchedulingPolicy` | [clusterSchedulingPolicy](clusterSchedulingPolicy.md) | No |  |
| `additionalTopologyKeys` | string[] | No | Additional Kubernetes topology label keys used by pod anti-affinity and topology spread for subsequently created or re-rendered clusters; existing Pods are not migrated automatically. Omit or use null during environment creation to store an empty list. Values must be valid Kubernetes qualified label keys. Infrastructure integrations or administrators must label all eligible nodes consistently; missing labels can cause unintended scheduling behavior and undermine failure-domain isolation. Too few eligible topology domains can leave Pods Pending under hard anti-affinity. If the Kubernetes LimitPodHardAntiAffinityTopology admission plugin is enabled, Pod creation is rejected for required anti-affinity using topology keys other than kubernetes.io/hostname, which can prevent the database cluster from becoming ready. |
| `tolerateDefaultTaints` | [tolerateDefaultTaints](tolerateDefaultTaints.md) | No |  |
| `systemComponentSchedulerPolicy` | [systemComponentSchedulerPolicy](systemComponentSchedulerPolicy.md) | No |  |
| `systemComponentReservationResourceClass` | [koordinatorReservationResourceClass](koordinatorReservationResourceClass.md) | No |  |

