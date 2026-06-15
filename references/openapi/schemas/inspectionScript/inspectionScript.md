# inspectionScript

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `name` | string | Yes |  |
| `displayName` | [localizedDescription](localizedDescription.md) | No |  |
| `engine` | string | Yes | The engine type this script is applicable to, such as cluster, mysql, node |
| `type` | string | Yes | The type of the script, such as "promQL" |
| `category` | [inspectionScriptCategory](inspectionScriptCategory.md) | Yes |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `scriptExpr` | string | Yes |  |
| `checkExpr` | string | No |  |
| `scopeType` | string | Yes | scope type, such as "system"/"global"/"org" |
| `scopeID` | string | No | The identifier of the scope, such as org_id |
| `scopeName` | string | No | The identifier of the scope, such as org_name |
| `enabled` | boolean | Yes |  |
| `unit` | string | No |  |
| `createdAt` | integer | No | Timestamp of creation time |
| `updatedAt` | integer | No | Timestamp of update time |

