# MongoExplainRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | database name |
| `collection` | string | No | collection name |
| `filter` | object | No | query filter to explain |
| `sort` | object | No | sort specification |
| `pipeline` | object[] | No | aggregation pipeline to explain |
| `collation` | object | No | MongoDB collation options |
| `maxTimeMS` | integer (int64) | No | maximum query execution time in milliseconds |
| `verbosity` | string | No | explain verbosity level (queryPlanner, executionStats, or allPlansExecution) |

