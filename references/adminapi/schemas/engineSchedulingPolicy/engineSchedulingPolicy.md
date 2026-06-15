# engineSchedulingPolicy

Engine-level default scheduling policy for a specific engine and engine mode.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Id of engine scheduling policy. |
| `schedulingPolicyType` | [schedulingPolicyType](schedulingPolicyType.md) | Yes |  |
| `engine` | string | Yes | Database engine that this policy applies to. Used together with `engineMode`. |
| `engineMode` | string | Yes | Engine mode that this policy applies to, such as `standalone` or `replication`. |
| `description` | string | No | Human-readable description of the engine scheduling policy. |

