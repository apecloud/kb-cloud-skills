# postgresqlWaitGraph

Wait graph related to the selected PID. It contains the selected session's ancestor and descendant wait edges that the backend can prove from the current snapshot; unrelated side branches are intentionally excluded.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nodes` | postgresqlWaitGraphNode[] | Yes |  |
| `edges` | postgresqlWaitGraphEdge[] | Yes |  |

