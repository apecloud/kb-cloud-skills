# sysbench

sysbench is the sysbench benchmark object

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
| `threads` | integer | No | Number of threads to use |
| `duration` | integer | No | the seconds of test duration |
| `tableSize` | integer | No | Number of rows per table |
| `tableNum` | integer | No | Number of tables |
| `testType` | [sysbenchTestType](sysbenchTestType.md) | No |  |
| `readPercent` | integer | No | Percentage of reads, only used for oltp_read_write_pct |
| `writePercent` | integer | No | Percentage of writes, only used for oltp_read_write_pct |
| `username` | string | Yes | Username for database |
| `password` | string | Yes | Password for database |
| `address` | string | Yes | Address for database |
| `extraArgs` | string | No | Extra arguments for sysbench |

