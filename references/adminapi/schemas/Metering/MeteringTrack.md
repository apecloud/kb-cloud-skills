# MeteringTrack

RTS metering track information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterID` | string | No | The ID of cluster |
| `orgName` | string | No | The Name of organization |
| `projectName` | string | No | The Name of project |
| `environmentID` | string | No | The ID of environment |
| `startTime` | integer (int64) | No | The clipped start time of the metering track in Unix timestamp (seconds since epoch) |
| `endTime` | integer (int64) | No | The clipped end time of the metering track in Unix timestamp (seconds since epoch) |
| `cpu` | string | No | The CPU usage tracked for the interval |
| `memory` | string | No | The memory usage tracked for the interval |
| `storage` | string | No | The storage usage tracked for the interval |
| `backup` | string | No | The backup usage tracked for the interval |

