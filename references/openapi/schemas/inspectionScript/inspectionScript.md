# inspectionScript

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `name` | string | Yes |  |
| `displayName` | [localizedDescription](localizedDescription.md) | No |  |
| `engine` | string | Yes | The engine type this script is applicable to, such as cluster, mysql, node |
| `type` | string | Yes | The type of the script, such as "promQL" or "manual" (requires evaluationMode=manual) |
| `category` | [inspectionScriptCategory](inspectionScriptCategory.md) | Yes |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `scriptExpr` | string | Yes | Collector expression for automatic modes; complete user instructions (up to 8192 UTF-8 bytes) for manual mode. Manual placeholders are not rendered. |
| `evaluationMode` | [inspectionEvaluationMode](inspectionEvaluationMode.md) | No |  |
| `checkExpr` | string | No |  |
| `criticality` | [inspectionCriticality](inspectionCriticality.md) | No |  |
| `warnThreshold` | number (double) | No | First-version warning threshold assumption. It documents the script contract and is not a permanent product conclusion. |
| `critThreshold` | number (double) | No | First-version critical threshold assumption. It documents the script contract and is not a permanent product conclusion. |
| `direction` | [inspectionThresholdDirection](inspectionThresholdDirection.md) | No |  |
| `remediation` | [localizedDescription](localizedDescription.md) | No |  |
| `docLink` | string | No |  |
| `scopeType` | string | Yes | scope type, such as "system"/"global"/"org" |
| `scopeID` | string | No | The identifier of the scope, such as org_id |
| `scopeName` | string | No | The identifier of the scope, such as org_name |
| `enabled` | boolean | Yes |  |
| `unit` | string | No |  |
| `createdAt` | integer | No | Timestamp of creation time |
| `updatedAt` | integer | No | Timestamp of update time |

