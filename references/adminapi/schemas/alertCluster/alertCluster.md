# alertCluster

Resource-scoped alert settings, shared by cluster and node endpoints. PATCH updates only supplied fields. Cluster settings apply to both tenant and administrator notifications.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disabled` | boolean | No | Disable all alerts for the resource. Existing rule and silence settings are preserved. |
| `disabledRules` | string[] | No | Alert names disabled only for this resource. An empty array clears all rule overrides; omission preserves them. |
| `silence` | [alertClusterSilence](alertClusterSilence.md) | No |  |
| `silenceActive` | boolean | No | Whether the configured silence window is active now, regardless of the alert master switch. |

