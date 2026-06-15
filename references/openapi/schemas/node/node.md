# node

node info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cpu` | integer (int64) | No | CPU cores of the node |
| `cpuStats` | [resourceStats](resourceStats.md) | No |  |
| `createdAt` | string (date-time) | Yes | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `hostName` | string | Yes | Host name of the node |
| `instanceType` | string | No | Instance type of the node |
| `ip` | string | Yes | IP address of the node |
| `memory` | integer (int64) | No | Memory of the node, unit is GiB |
| `memoryStats` | [resourceStats](resourceStats.md) | No |  |
| `zone` | string | No | Zone of the node |
| `region` | string | No | Region of the node |
| `nodeGroup` | string | No | Node Group of the node |
| `controlPlane` | boolean | No | node is in control plane |
| `dataPlane` | boolean | No | node is in data plane |
| `managed` | boolean | No | Whether the node is managed (has data-plane or control-plane label) |
| `status` | [nodeStatus](nodeStatus.md) | Yes |  |

