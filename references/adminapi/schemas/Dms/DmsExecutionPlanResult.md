# DmsExecutionPlanResult

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `originSQL` | string | No |  |
| `explainSQL` | string | No |  |
| `engineType` | string | No |  |
| `mode` | [DmsExecutionPlanMode](DmsExecutionPlanMode.md) | No |  |
| `planMode` | [DmsExecutionPlanPlanningMode](DmsExecutionPlanPlanningMode.md) | No |  |
| `parameterized` | boolean | No |  |
| `parameterCount` | integer (int64) | No |  |
| `hasActualStats` | boolean | No |  |
| `rawFormat` | [DmsExecutionPlanRawFormat](DmsExecutionPlanRawFormat.md) | No |  |
| `rawPlan` | object | No | Engine-native raw plan payload exposed for fallback display. SDKs model it as a free-form JSON object. |
| `rootNodeIds` | string[] | No |  |
| `nodes` | DmsExecutionPlanNode[] | No |  |
| `edges` | DmsExecutionPlanEdge[] | No |  |
| `summary` | [DmsExecutionPlanSummary](DmsExecutionPlanSummary.md) | No |  |
| `warnings` | DmsExecutionPlanWarning[] | No |  |
| `fallbackTable` | [DmsQueryResponse](DmsQueryResponse.md) | No |  |

