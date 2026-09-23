# DmsExecutionPlanNode

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `parentIds` | string[] | No |  |
| `childIds` | string[] | No |  |
| `order` | integer (int64) | No |  |
| `category` | [DmsExecutionPlanNodeCategory](DmsExecutionPlanNodeCategory.md) | No |  |
| `nodeType` | string | No |  |
| `label` | string | No |  |
| `relationName` | string | No |  |
| `schemaName` | string | No |  |
| `alias` | string | No |  |
| `indexName` | string | No |  |
| `cost` | [DmsExecutionPlanNodeCost](DmsExecutionPlanNodeCost.md) | No |  |
| `rows` | [DmsExecutionPlanNodeRows](DmsExecutionPlanNodeRows.md) | No |  |
| `timing` | [DmsExecutionPlanNodeTiming](DmsExecutionPlanNodeTiming.md) | No |  |
| `conditions` | [DmsExecutionPlanNodeConditions](DmsExecutionPlanNodeConditions.md) | No |  |
| `details` | object | No |  |

