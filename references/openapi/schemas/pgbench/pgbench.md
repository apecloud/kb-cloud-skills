# pgbench

pgbench is the pgbench benchmark object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `step` | [benchmarkStep](benchmarkStep.md) | No |  |
| `limitCpu` | string | No | the cpu limit for test container |
| `limitMemory` | string | No | the memory limit for test container |
| `requestCpu` | string | No | the cpu request for test container |
| `requestMemory` | string | No | the memory request for test container |
| `name` | string | No | the name of benchmark |
| `cluster` | string | Yes | the cluster name |
| `database` | string | Yes | the database name |
| `username` | string | Yes | Username for database |
| `password` | string | Yes | Password for database |
| `address` | string | Yes | Address for database |
| `scale` | integer | No | Scale of pgbench |
| `clients` | integer | No | Number of clients to run |
| `threads` | integer | No | Number of threads to use |
| `duration` | integer | No | the seconds of test duration |
| `selectOnly` | boolean | No | Run select only test |
| `extraArgs` | string | No | Extra arguments for pgbench |

