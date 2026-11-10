# opsVolumeExpand

Expand component volumes and explicit targets for components with template expansion enabled.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `instanceTemplates` | instanceTemplateVolumeExpand[] | No | Required when the current mode component instanceTemplate.ops includes storageExpansion; otherwise omit for component-level expansion. Explicit targets require this capability. Every configured template must explicitly specify the same volume names and target capacities as component-level volumes. Names identify templates, not Pods. Targets are forwarded together in one OpsRequest without filling in, merging, or removing template targets. KubeBlocks may materialize template volumeClaimTemplates for explicitly targeted inherited volumes. |
| `component` | string | Yes |  |
| `volumes` | opsVolumeExpandVolumesItems0[] | Yes |  |

