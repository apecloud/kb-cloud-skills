# cdcToolTemplate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `image` | string | No |  |
| `command` | string[] | No |  |
| `args` | string[] | No |  |
| `replicas` | integer (int32) | No |  |
| `configFileName` | string | No |  |
| `configFilePath` | string | No |  |
| `configResourceType` | [cdcConfigResourceType](cdcConfigResourceType.md) | No |  |
| `configFormat` | [cdcConfigFormatType](cdcConfigFormatType.md) | No |  |
| `localRecoveryEnabled` | boolean | No | whether to enable local recovery feature |
| `localRecoveryStorageClass` | string | No |  |
| `localRecoveryStorageSize` | integer | No | size of local recovery storage, the unit is MiB |
| `localRecoveryPath` | string | No |  |
| `LogPath` | string | No |  |
| `startupTimeoutMinutes` | integer (int32) | No |  |
| `properties` | object | No |  |

