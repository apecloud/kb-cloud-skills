# storageClassInfo

StorageClassInfo provides detailed information about a specific storage class.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | the name of the storage class |
| `creationTimestamp` | string | Yes | the creation time of the storage class |
| `provisioner` | string | Yes | the provisioner of the storage class |
| `parameters` | object | No | the parameters of the storage class |
| `labels` | object | No | the labels of the storage class |
| `annotations` | object | No | the annotations of the storage class |
| `reclaimPolicy` | string | Yes | the reclaim policy of the storage class |
| `allowVolumeExpansion` | boolean | Yes | whether allow volume expansion |
| `volumeBindingMode` | string | Yes | the volume binding mode of the storage class |
| `pvcCount` | string | Yes | the number of PVCs |
| `allowClone` | boolean | Yes | whether allow clone |
| `allowSnapshot` | boolean | Yes | whether allow snapshot |
| `isDefaultClass` | boolean | Yes | whether is default class |
| `type` | string | Yes | the type of the storage class |
| `hostPath` | string | No | the host path when using local storage provisioner |
| `mountOptions` | string[] | No | the mount options of the storage class |
| `createdAt` | string (date-time) | No | the creation time of the storage class |
| `description` | string | Yes | the description of the storage class |
| `displayName` | string | Yes | the display name of the storage class |
| `enabled` | boolean | Yes | whether the storage class is enabled |
| `id` | string | Yes | the id of the storage class |
| `updatedAt` | string (date-time) | No | the update time of the storage class |
| `minSizeGi` | integer | No | the minimum size of the storage class |

