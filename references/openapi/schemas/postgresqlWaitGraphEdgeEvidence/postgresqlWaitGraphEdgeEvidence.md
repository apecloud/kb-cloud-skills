# postgresqlWaitGraphEdgeEvidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `lockRows` | postgresqlLockRow[] | Yes | Lock rows the backend can associate with this wait edge. |
| `limitation` | string | Yes | Non-empty when the backend cannot associate precise lock rows with this edge. |

