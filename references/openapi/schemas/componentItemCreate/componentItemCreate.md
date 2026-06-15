# componentItemCreate

ComponentItem is the information of a component

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes | component type, refer to componentDef and support NamePrefix |
| `compNum` | integer | No | The number of components, if often used as shards number |
| `replicas` | integer | No | The number of replicas, for standalone mode, the replicas is 1, for raftGroup mode, the default replicas is 3. |
| `skipResourceConstraints` | boolean | No | Whether to skip resource constraint validation when creating cluster |
| `classCode` | string | No |  |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |
| `storageClass` | string | No | StorageClass name |
| `volumes` | componentVolumeItem[] | No |  |
| `systemAccountSecretName` | string | No | The name of the secret that contains the system account credentials |

