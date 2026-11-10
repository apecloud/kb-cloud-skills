# componentItem

ComponentItem is the information of a component

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotations` | object | No | User-provided component annotations. Does not include chart defaults or system-generated values. |
| `labels` | object | No | User-provided component labels. Does not include chart defaults or system-generated values. |
| `nodeGroup` | string | No | Optional host group in this environment. Explicit placement does not inherit an upper-level host group. |
| `availabilityZone` | string | No | Explicit component AZ selection, if configured. |
| `instanceTemplates` | instanceTemplateCreate[] | No | Instance template assignments with effective replicas, placement and storage class, and user-provided env, labels and annotations. |
| `name` | string | No | component name |
| `component` | string | No | component type, refer to componentDef and support NamePrefix |
| `compNum` | integer | No | number of components |
| `replicas` | integer | No | The number of replicas, for standalone mode, the replicas is 1, for raftGroup mode, the default replicas is 3. |
| `classCode` | string | No |  |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |
| `storageClass` | string | No | StorageClass name |
| `volumes` | componentVolumeItem[] | No |  |
| `codeShort` | string | No | Cluster main component codeShort |
| `systemAccountSecretName` | string | No | The name of the secret that contains the system account credentials |
| `network` | [componentNetwork](componentNetwork.md) | No |  |

