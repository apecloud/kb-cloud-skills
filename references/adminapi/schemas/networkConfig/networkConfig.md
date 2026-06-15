# networkConfig

Configuration of networking for this environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nodePortEnabled` | boolean | No | Enable node port service for this environment |
| `lbEnabled` | boolean | No | Enable load balancer service for this environment |
| `domainEnabled` | boolean | No | Enable domain service for this environment |
| `internetLBEnabled` | boolean | No | Enable the Internet load balancer service for this environment |
| `networkModes` | networkMode[] | No | Network modes of the environment |

