# instanceTemplateCreate

Create assignment for one instance template. name and replicas are required. env, annotations, labels, availabilityZone, nodeGroup and storageClass are optional overlays. The request must include every chart-rendered instance template exactly once. Explicit placement requires availabilityZone and optionally accepts nodeGroup, without inheriting upper-level AZ or NodeGroup. Omitting both leaves SchedulingPolicy unset for KubeBlocks default inheritance. Hostname, user scheduling rules and additional topology keys are preserved.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `nodeGroup` | string | No | Optional host group in this environment and the explicitly selected availabilityZone. Requires availabilityZone; no upper-level host group is inherited. |
| `name` | string | Yes | Instance template name; must match a chart-rendered instance. |
| `replicas` | integer | Yes | Replica count for this instance template. |
| `availabilityZone` | string | No | Single AZ for explicit template placement (topology.kubernetes.io/zone). Must be enabled in the environment and is required when nodeGroup is specified. An omitted nodeGroup does not inherit the component or cluster host group. Omitting both leaves SchedulingPolicy unset for KubeBlocks inheritance. |
| `storageClass` | string | No | StorageClass name for all persistent volumes in this template. Copied from component volumeClaimTemplates, preserving volume sizes and other settings while overriding storageClassName. Chart instance volume templates are cleared; omitted or empty leaves instance volumeClaimTemplates unset. |
| `env` | object[] | No | Simple env vars (name and value only) merged into this template. valueFrom is not supported; overlaying a name clears any chart valueFrom. |
| `annotations` | object | No | Annotation map (string key to string value). Merged into this template; same-name keys overwritten. Chart keys are not deleted. |
| `labels` | object | No | Label map (string key to string value). Merged into this template; same-name keys overwritten. Chart keys are not deleted. The apps.kubeblocks.io/instance-template label is managed by the system and must equal the template name if supplied. |

## Nested Fields

### `env`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `value` | string | Yes | Plain string value only. valueFrom is not supported. |

