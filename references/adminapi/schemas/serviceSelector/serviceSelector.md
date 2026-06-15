# serviceSelector

This definition of component/service/port is in line with kubeblocks api
appsv1.ServiceRefServiceSelector. Read kubeblocks documentation for more information.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `mode` | string | Yes | referenced cluster's mode |
| `component` | string | Yes |  |
| `service` | string | Yes |  |
| `port` | string | Yes |  |
| `credentialComponent` | string | No |  |
| `credentialName` | string | No |  |

