# storage

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/storageProviders` | List storage providers for storage | [View](../operations/listStorageProviders.md) |
| GET | `/admin/v1/environments/{environmentName}/storages` | List storages | [View](../operations/listStorages.md) |
| POST | `/admin/v1/environments/{environmentName}/storages` | Create a storage | [View](../operations/createStorage.md) |
| GET | `/admin/v1/environments/{environmentName}/storages/{storageName}` | Get a storage | [View](../operations/getStorage.md) |
| POST | `/admin/v1/environments/{environmentName}/storages/{storageName}` | Update a storage | [View](../operations/updateStorage.md) |
| DELETE | `/admin/v1/environments/{environmentName}/storages/{storageName}` | Delete a storage | [View](../operations/deleteStorage.md) |
| POST | `/admin/v1/storageCheck` | Check if storage can be accessed | [View](../operations/checkStorage.md) |
| POST | `/admin/v1/environments/{environmentName}/storages/{storageName}/importbackup` | scan and import backup records from storage | [View](../operations/importBackup.md) |
