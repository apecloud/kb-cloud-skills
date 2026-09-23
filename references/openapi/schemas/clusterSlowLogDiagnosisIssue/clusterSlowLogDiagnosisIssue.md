# clusterSlowLogDiagnosisIssue

A single detected slow log diagnosis issue

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | string | No |  |
| `severity` | string | No | Issue severity. Current values are info, low, medium, and high. |
| `source` | string | No | Evidence source used by the local rule |
| `message` | [localizedDescription](localizedDescription.md) | No |  |
| `evidence` | clusterSlowLogLocalizedText[] | No |  |
| `nodeId` | string | No |  |

