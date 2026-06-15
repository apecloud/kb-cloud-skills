# component

Component info in environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `kubernetesVersion` | string | No | Kubernetes version of the environment |
| `kbVersion` | string | No | KubeBlocks version of the environment |
| `geminiVersion` | string | No | Gemini version of the environment |
| `oteldVersion` | string | No | Oteld version of the environment |
| `imageRegistry` | string | No | Image registry URL used by the environment. Must match image_registries.url, not image_registries.name. |
| `defaultStorageClass` | string | Yes | Default storage class that used by KubeBlocks to create cluster |
| `cpuOvercommitRatio` | number (double) | No | CPU overcommit ratio of this environment |
| `memoryOvercommitRatio` | number (double) | No | Memory overcommit ratio of this environment |
| `replicas` | integer | No | the replicas of core component, such as kubeblocks and gemini |
| `namespaces` | string[] | No | Namespace info for environment |

