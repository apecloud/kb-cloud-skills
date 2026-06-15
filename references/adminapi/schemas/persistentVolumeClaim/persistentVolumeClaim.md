# persistentVolumeClaim

persistentVolumeClaim provides detailed information about the PVC .

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nameSpace` | string | Yes | the namespace of the PVC |
| `name` | string | Yes | the name of the PVC |
| `phase` | string | Yes | the phase of the PVC |
| `capacity` | number (double) | No | the capacity of the PVC |
| `usage` | number (double) | No | the usage of the PVC |
| `accessMode` | string | No | access mode of the PVC |
| `volumeName` | string | No | the persistentvolume of the PVC |
| `node` | string | No | the node of the PVC |
| `orgName` | string | No | the org name of the PVC |
| `clusterName` | string | No | the cluster name of the PVC |

