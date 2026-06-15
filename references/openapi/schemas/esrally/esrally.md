# esrally

esrally is the Elasticsearch Rally benchmark object

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
| `username` | string | Yes | Username for Elasticsearch |
| `password` | string | No | Password for Elasticsearch |
| `address` | string | Yes | Address for Elasticsearch |
| `onError` | [esrallyOnError](esrallyOnError.md) | No |  |
| `telemetry` | esrallyTelemetry[] | No | Rally telemetry devices |
| `dataProfile` | [esrallyDataProfile](esrallyDataProfile.md) | No |  |
| `documentCount` | integer | No | Number of generated documents |
| `workload` | [esrallyWorkload](esrallyWorkload.md) | No |  |
| `extraArgs` | string | No | Extra arguments for esrally |

