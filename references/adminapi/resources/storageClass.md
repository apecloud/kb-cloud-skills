# storageClass

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/environments/{environmentName}/storageClasses` | List storage classes of a environment | [View](../operations/listStorageClasses.md) |
| POST | `/admin/v1/environments/{environmentName}/storageClasses` | create storage class | [View](../operations/createStorageClass.md) |
| GET | `/admin/v1/environments/{environmentName}/storageProvisioners` | List the provisioners that can be used by storage class of a environment | [View](../operations/listStorageProvisioners.md) |
| GET | `/admin/v1/environments/{environmentName}/storageClasses/{storageClassName}` | get storage class | [View](../operations/getStorageClass.md) |
| DELETE | `/admin/v1/environments/{environmentName}/storageClasses/{storageClassName}` | Delete storage class | [View](../operations/deleteStorageClass.md) |
| PATCH | `/admin/v1/environments/{environmentName}/storageClasses/{storageClassName}` | Update storage class | [View](../operations/updateStorageClass.md) |
| GET | `/admin/v1/environments/{environmentName}/storageClasses/{storageClassName}/pvcs` | get persistentvolumeclaim list of the storage class | [View](../operations/listStorageClassPvcs.md) |
| GET | `/admin/v1/environments/{environmentName}/storageClasses/{storageClassName}/nodeStats` | get node stats of the storage class | [View](../operations/listStorageClassNodeStats.md) |
