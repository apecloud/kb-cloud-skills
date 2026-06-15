# benchmark

Benchmark is the benchmark object

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | ID of benchmark |
| `name` | string | No | Name of benchmark |
| `type` | [benchmarkType](benchmarkType.md) | No |  |
| `config` | string | No | Config of benchmark |
| `prepareLog` | string | No | the log of benchmark in prepare stage |
| `runLog` | string | No | the log of benchmark in run stage |
| `cleanupLog` | string | No | the log of benchmark in cleanup stage |
| `result` | string | No | the result of benchmark, only available when benchmark is complete |
| `message` | string | No | the message of benchmark, only available when benchmark is failed |
| `cluster` | string | No | the cluster name |
| `clusterID` | string | No | the cluster id |
| `command` | string | No | the actual command executed during the benchmark run stage |
| `database` | string | No | the database name |
| `completionTimestamp` | string (date-time) | No | the completion timestamp of benchmark |
| `createdAt` | string (date-time) | No | the create timestamp of benchmark |
| `extra` | string | No | extra args for benchmark |
| `status` | [benchmarkStatus](benchmarkStatus.md) | No |  |

