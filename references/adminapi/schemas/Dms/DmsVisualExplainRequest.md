# DmsVisualExplainRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `query` | string | No | the sql string |
| `database` | string | No | the database for explaining the SQL |
| `analyze` | boolean | No | whether to run an actual/analyze plan when the engine supports it |

