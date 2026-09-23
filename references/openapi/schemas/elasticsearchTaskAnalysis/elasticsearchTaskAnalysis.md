# elasticsearchTaskAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tasks` | elasticsearchTask[] | Yes | List of currently running tasks, sorted by running time in descending order |
| `hotThreads` | elasticsearchHotThreads[] | Yes |  |
| `sources` | performanceTrendSource[] | Yes |  |
| `warnings` | string[] | Yes |  |
| `collectedAt` | string | Yes |  |

