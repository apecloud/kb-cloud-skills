# serviceRef

defines a serviceRef that references service provided by other cluster or external service.
Only one of cluster or serviceDescriptor field should be set.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | refers to the serviceRef name defined in engineoption |
| `cluster` | string | No | the cluster name that will be used in serviceRef. The referenced cluster should 
be at the same organization as the current cluster.
 |
| `clusterDefinition` | string | No | the cluster definition of the referenced cluster. |
| `serviceDescriptor` | [serviceDescriptor](serviceDescriptor.md) | No |  |

