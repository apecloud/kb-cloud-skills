# orgDeletionPreview

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `orgID` | string | Yes |  |
| `name` | string | Yes |  |
| `status` | string | Yes |  |
| `expiredAt` | string (date-time) | Yes |  |
| `purgeError` | string | No |  |
| `action` | string | Yes |  |
| `canProceed` | boolean | Yes |  |
| `blockers` | orgDeletionBlocker[] | Yes |  |
| `configurations` | orgConfigurationSummary[] | Yes |  |
| `retainedResources` | orgRetainedResource[] | Yes |  |

