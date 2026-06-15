# nodePoolNode

Node info for environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `availabilityZone` | string | Yes |  |
| `markControlPlane` | boolean | No |  |
| `markDataPlane` | boolean | No | Mark the node as a data plane, which will always be true when markControlPlane is not specified |
| `nodeGroup` | string | No | The node group to assign this node to |

