# environmentDelete

Environment deletion option

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cleanCloudResources` | boolean | No | clean up resources in the cloud (only valid if creation is done by role ARN) |
| `minio` | [cloudResourceCleanPolicy](cloudResourceCleanPolicy.md) | No |  |
| `victoriaMetrics` | [cloudResourceCleanPolicy](cloudResourceCleanPolicy.md) | No |  |

