# modeServiceRef

Defines a ServiceRef for a cluster, enabling access to both external services and
Services provided by other Clusters. The defined serviceRef must be provided when creating cluster.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name will be referenced in clusterCreate request. The name should also be defined in `.components`
so that frontend can use it to get proper localized title.
 |
| `engineName` | string | Yes | The engine to be used in serviceRef. This field is used to filter clusters. |
| `modes` | string[] | No | The mode to be used in serviceRef. This field is used to filter clusters. If not set, it means all modes are supported. |
| `addressStyle` | [serviceDescriptorAddressStyle](serviceDescriptorAddressStyle.md) | Yes |  |
| `disableManualInput` | boolean | No | whether to disable manual input of the service reference. If set to true, users can only select from the serviceRefs provided by list clusters api. |
| `helmValuePath` | object | Yes | The path to be used in values. Separated with commas. ClusterCreate API will use these path to override values in the cluster chart. |
| `serviceSelectors` | serviceSelector[] | No | ServiceSelectors will map cluster's mode to a serviceSelector. The serviceSelector
will be used to provide the corresponding helm values.
If no serviceSelector is matched, the corresponding helm value will not be set.
 |

## Nested Fields

### `helmValuePath`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `namespace` | string | Yes | the namespace of the referenced Cluster or the namespace of the referenced ServiceDescriptor object. |
| `cluster` | string | Yes | the name of the referenced Cluster |
| `component` | string | No | see serviceSelectors |
| `service` | string | No | see serviceSelectors |
| `port` | string | No | see serviceSelectors |
| `credentialComponent` | string | No | see serviceSelectors |
| `credentialName` | string | No | see serviceSelectors |
| `serviceDescriptor` | string | Yes | the name of the referenced serviceDescriptor |
| `mode` | string | No | hints for addon to determine if we are using an integrated component or a serviceRef. Will be set to `serviceRef` or `component`.
This field is required when a serviceRef can be replaced by a component.
 |

