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
| `title` | object | No | The localized title of the serviceRef. |
| `optional` | boolean | No | whether this serviceRef is optional. If set to true, the cluster can be created without providing this serviceRef. |
| `engineName` | string | Yes | The default engine to be used in serviceRef. This field is used as the fallback engine filter and default create entry. |
| `modes` | string[] | No | The mode to be used in serviceRef. This field is used to filter clusters. If not set, it means all modes are supported. |
| `addressStyle` | [serviceDescriptorAddressStyle](serviceDescriptorAddressStyle.md) | Yes |  |
| `disableManualInput` | boolean | No | whether to disable manual input of the service reference. If set to true, users can only select from the serviceRefs provided by list clusters api. |
| `disableAutoCreateServiceDescriptor` | boolean | No | whether to disable auto creating the ServiceDescriptor object for this serviceRef.
If set to false, the serviceDescriptor content (host/port/username/password) will be
set directly into the helm values under the helmValuePath.serviceDescriptor path.
If omitted, the generated ServiceDescriptor name will be set instead.
 |
| `disableRelatedCluster` | boolean | No | whether to disable selecting a related cluster created in the platform for this
serviceRef. If set to true, the frontend should only allow manual input instead
of selecting from the clusters provided by the list clusters api.
 |
| `extraForManualInput` | object | No | Extra form field definitions for manual input of the serviceRef. The keys are the
field names and the frontend renders them as input items. The user-entered values
are passed in ClusterCreate serviceRefs[].extraForManualInput and mapped to helm
values via helmValuePath.extraForManualInput.
 |
| `helmValuePath` | object | Yes | The path to be used in values. Separated with commas. ClusterCreate API will use these path to override values in the cluster chart. |
| `serviceSelectors` | serviceSelector[] | No | ServiceSelectors will map cluster's mode to a serviceSelector. The serviceSelector
will be used to provide the corresponding helm values.
If no serviceSelector is matched, the corresponding helm value will not be set.
 |
| `serviceVersionCompatibility` | modeServiceRefVersionCompatibility[] | No | Service version compatibility rules for this serviceRef. The create API uses
these rules to reject incompatible referenced clusters, and the frontend can
use them to filter or explain selectable referenced clusters.
 |
| `updatable` | boolean | No | whether the serviceRef can be updated. If set to false, the frontend should not allow users to update the serviceRef. |

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
| `serviceDescriptor` | string | No | the name of the referenced serviceDescriptor |
| `mode` | string | No | hints for addon to determine if we are using an integrated component or a serviceRef. Will be set to `serviceRef` or `component`.
This field is required when a serviceRef can be replaced by a component.
 |
| `extraForManualInput` | string | No | the helm value path prefix for the extraForManualInput fields of this serviceRef.
ClusterCreate API will map each key of serviceRefs[].extraForManualInput to
`<extraForManualInput>.<key>` in the cluster chart values.
 |

