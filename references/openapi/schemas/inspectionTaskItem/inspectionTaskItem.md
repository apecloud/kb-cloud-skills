# inspectionTaskItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `taskID` | string | No |  |
| `scriptID` | string | No |  |
| `scriptName` | [localizedDescription](localizedDescription.md) | No |  |
| `scriptDescription` | [localizedDescription](localizedDescription.md) | No |  |
| `scriptCategory` | string | No | Category used to group inspection items, such as availability, performance, capacity, or backup. |
| `resourceType` | string | No | Type of the inspected resource, such as cluster or node; resourceID and resourceName identify the target. |
| `resourceID` | string | No |  |
| `resourceName` | string | No |  |
| `status` | string | No | Execution state, such as Running, Completed, or Failed. Use severity for the health conclusion. For manual items, Completed means instructions are available, not that the user has performed them. |
| `result` | string | No | Textual observation or execution message for display. It may contain nonnumeric information or an error; use severity for the health conclusion. Manual instructions are stored in evidence.ruleSnapshot.scriptExpr. |
| `valueNum` | number (double) | No | Numeric observation when available, including numeric information collected by info items. Omitted when no numeric observation exists, including manual guidance. Use with unit and thresholds for numeric displays. |
| `warnThreshold` | number (double) | No | Warning threshold interpreted using direction and the same unit as valueNum. Omitted when no numeric warning threshold is configured. |
| `critThreshold` | number (double) | No | Critical threshold interpreted using direction and the same unit as valueNum. Omitted when no numeric critical threshold is configured. |
| `direction` | [inspectionThresholdDirection](inspectionThresholdDirection.md) | No |  |
| `criticality` | [inspectionCriticality](inspectionCriticality.md) | No |  |
| `evidence` | [inspectionTaskItemEvidence](inspectionTaskItemEvidence.md) | No |  |
| `statusChangedAt` | string (date-time) | No | Item-level timestamp for when this item's status was last evaluated or changed. |
| `remediation` | [localizedDescription](localizedDescription.md) | No |  |
| `docLink` | string | No | Link to documentation explaining this inspection item and recommended actions. |
| `severity` | string | No | Health conclusion: red (critical), yellow (warning), green (healthy), unknown (cannot evaluate), or info (automatically collected information). Manual guidance returns unknown and retains its criticality. Unknown and info do not contribute to health scoring; Completed for manual guidance means instructions are available, not user completion. |
| `unit` | string | No | Display unit for the inspection result and thresholds, such as percent, seconds, or bytes. Empty when no unit applies. |
| `createdAt` | string (date-time) | No |  |
| `updatedAt` | string (date-time) | No |  |

