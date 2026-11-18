# componentItemCreate

ComponentItem is the information of a component

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotations` | object | No | User-provided component annotations, merged over chart defaults. Platform-managed keys cannot be overridden. Omitted or empty preserves defaults; empty string values are literal values, not deletions. |
| `labels` | object | No | User-provided component labels, merged over chart defaults. Key prefixes before / matching kubeblocks.io, kubernetes.io, k8s.io or any of their subdomains are reserved. Keys and values must satisfy Kubernetes label syntax. Omitted or empty preserves defaults; empty string values are literal values, not deletions. |
| `nodeGroup` | string | No | Optional host group in this environment and the explicitly selected availabilityZone. Requires availabilityZone; no upper-level host group is inherited. |
| `availabilityZone` | string | No | Single AZ for explicit component placement. Must be enabled in the environment and is required when nodeGroup is specified. An omitted nodeGroup does not inherit the cluster host group. Omitting both retains cluster scheduling. |
| `component` | string | Yes | component type, refer to componentDef and support NamePrefix |
| `compNum` | integer | No | The number of components, if often used as shards number |
| `replicas` | integer | No | The number of replicas, for standalone mode, the replicas is 1, for raftGroup mode, the default replicas is 3. When instanceTemplates is provided, this must equal the sum of all template replica counts. |
| `instanceTemplates` | instanceTemplateCreate[] | No | Per-template replicas and optional overlays (env, annotations, labels, availability zone, storage class). Required when the current mode component declares instanceTemplate in engine_options; otherwise omit. Names must exactly match all chart-rendered instances, without missing, extra, or duplicate names; order does not matter. Component replicas must equal the sum of all requested instance template replica counts. |
| `skipResourceConstraints` | boolean | No | Whether to skip resource constraint validation when creating cluster |
| `classCode` | string | No |  |
| `cpu` | number (double) | No | CPU cores. |
| `memory` | number (double) | No | Memory, the unit is Gi. |
| `storageClass` | string | No | StorageClass name |
| `volumes` | componentVolumeItem[] | No |  |
| `systemAccountSecretName` | string | No | The name of the secret that contains the system account credentials |
| `network` | [componentNetwork](componentNetwork.md) | No |  |

