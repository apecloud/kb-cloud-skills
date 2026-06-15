# storageClassCreate

StorageClassCreate provides detailed creation information about a storage class.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | the name of the storage class |
| `provisioner` | string | No | the provisioner of the storage class |
| `labels` | object | No | the labels of the storage class |
| `annotations` | object | No | the annotations of the storage class |
| `parameters` | object | No | the parameters of the storage class |
| `reclaimPolicy` | [storageClassReclaimPolicy](storageClassReclaimPolicy.md) | Yes |  |
| `allowVolumeExpansion` | boolean | No | whether allow volume expansion |
| `volumeBindingMode` | [storageClassVolumeBindingMode](storageClassVolumeBindingMode.md) | Yes |  |
| `allowClone` | boolean | No | whether allow clone |
| `allowSnapshot` | boolean | No | whether allow snapshot |
| `isDefaultClass` | boolean | No | whether is default class |
| `type` | string | No | the type of the storage class |
| `hostPath` | string | No | the host path when using local storage provisioner |
| `mountOptions` | string[] | No | the mount options of the storage class |
| `description` | string | Yes | the description of the storage class |
| `displayName` | string | Yes | the display name of the storage class |
| `enabled` | boolean | Yes | whether the storage class is enabled |

