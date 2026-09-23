# inspectionTaskCreate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `engines` | string[] | No | Engine names to inspect in the path organization. Omit or pass an empty array to inspect all engines. |
| `clusterIDs` | string[] | No | Cluster IDs to inspect in the path organization. Omit or pass an empty array to inspect all clusters selected by engines. |
| `timeRangeStart` | string (date-time) | No | Start of the inspection window. If either bound is omitted, defaults to the preceding 24 hours. |
| `timeRangeEnd` | string (date-time) | No |  |
| `savedDays` | integer (int64) | No | Report retention in days. Zero uses the existing default retention policy. |

