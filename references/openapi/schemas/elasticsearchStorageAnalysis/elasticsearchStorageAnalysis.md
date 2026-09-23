# elasticsearchStorageAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `indices` | elasticsearchIndexStorage[] | Yes |  |
| `allocations` | elasticsearchNodeAllocation[] | Yes |  |
| `watermarks` | [elasticsearchDiskWatermarks](elasticsearchDiskWatermarks.md) | Yes |  |
| `sources` | performanceTrendSource[] | Yes |  |
| `warnings` | string[] | Yes |  |
| `collectedAt` | string | Yes |  |

