# ycsb

ycsb is the ycsb benchmark object

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
| `database` | string | No | the database name |
| `cluster` | string | Yes | the cluster name |
| `username` | string | Yes | Username for database |
| `password` | string | No | Password for database |
| `address` | string | Yes | Address for database |
| `recordCount` | integer | No | Number of records to load into database |
| `operationCount` | integer | No | Number of operations to perform |
| `readProportion` | integer | No | Percentage of read operations |
| `updateProportion` | integer | No | Percentage of update operations |
| `insertProportion` | integer | No | Percentage of insert operations |
| `readModifyWriteProportion` | integer | No | Percentage of read-modify-write operations |
| `scanProportion` | integer | No | Percentage of scan operations |
| `threads` | integer | No | Number of client threads to run |
| `extraArgs` | string | No | Extra arguments for ycsb |
| `redisMode` | [ycsbRedisMode](ycsbRedisMode.md) | No |  |
| `redisSentinelMaster` | string | No | Redis sentinel master |
| `redisSentinelUsername` | string | No | Redis sentinel username |
| `redisSentinelPassword` | string | No | Redis sentinel password |

