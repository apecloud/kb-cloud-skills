# engineSchedulingRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Id of engine scheduling rule. |
| `name` | string | Yes | Rule name, used to reference this rule when applying scheduling policies to a cluster. |
| `engine` | string | Yes | Database engine type this rule applies to. Used to match rules to clusters by engine. |
| `engineMode` | string | Yes | Cluster mode this rule applies to. Used to match rules to clusters by mode. |
| `targetSelector` | target[] | Yes | Selects the two mutually exclusive targets that this rule applies to. The array length must be exactly 2. |
| `schedulingPolicyType` | [schedulingPolicyType](schedulingPolicyType.md) | Yes |  |
| `description` | string | No | Optional description of the scheduling rule. |
| `default` | boolean | No | Indicates whether this rule is used as the fallback when no other rule matches. |

