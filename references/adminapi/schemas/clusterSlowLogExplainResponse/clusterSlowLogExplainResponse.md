# clusterSlowLogExplainResponse

Explain response for a selected slow log template sample

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `templateId` | string | No | Query template identifier |
| `sql` | string | No | Concrete sample SQL used for EXPLAIN |
| `sqlType` | string | No | Statement type accepted by the backend safety check |
| `database` | string | No | Database selected from the slow log sample |
| `normalizedQuery` | string | No | Normalized SQL template from oteld |
| `sampleTimestamp` | integer (int64) | No | Timestamp of the selected sample in epoch nanoseconds |
| `executionTime` | number (double) | No | Execution time of the selected sample in seconds |
| `sample` | [clusterExecutionLogItem](clusterExecutionLogItem.md) | No |  |
| `explainResult` | [DmsQueryResponse](DmsQueryResponse.md) | No |  |

