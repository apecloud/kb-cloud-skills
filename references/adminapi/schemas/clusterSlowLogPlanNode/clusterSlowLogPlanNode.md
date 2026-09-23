# clusterSlowLogPlanNode

Best-effort visual execution plan node parsed from EXPLAIN.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `parentId` | string | No |  |
| `operation` | string | No |  |
| `table` | string | No |  |
| `accessType` | string | No |  |
| `detail` | string | No |  |
| `costStart` | number (double) | No |  |
| `costEnd` | number (double) | No |  |
| `rows` | integer (int64) | No |  |
| `issueCode` | string | No |  |
| `issueSeverity` | string | No |  |

