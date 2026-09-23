# loadBalancerAnnotations

Provider-neutral annotations applied to load balancer Services by exposure type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vpc` | object | Yes | Annotations used for load balancers exposed inside the VPC. |
| `internet` | object | Yes | Annotations used for load balancers exposed to the Internet. |

