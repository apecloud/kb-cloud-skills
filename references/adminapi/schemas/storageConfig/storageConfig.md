# storageConfig

Storage config for environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `storages` | environmentStorage[] | Yes | these storages will be created |
| `backup` | object | No | the storage config for backup |

## Nested Fields

### `backup`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `storageIndex` | integer (int64) | No | Zero-based index of the default backup storage. Required for multiple storages when storageName is omitted. |
| `storageName` | string | No | the name of storage |
| `backupRepoName` | string | No | the backup repo name which will be init |
| `defaultBackupRepo` | boolean | No | judge whether to set the backup is default which will be init |

