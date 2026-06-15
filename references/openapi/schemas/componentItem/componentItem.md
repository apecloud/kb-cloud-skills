# componentItem

ComponentItem is the information of a component

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
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

