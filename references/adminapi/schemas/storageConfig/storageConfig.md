# storageConfig

Storage config for environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `storages` | environmentStorage[] | Yes | these storages will be created |
| `backup` | object | Yes | the storage config for backup |

## Nested Fields

### `backup`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `storageName` | string | Yes | the name of storage |
| `backupRepoName` | string | Yes | the backup repo name which will be init |
| `defaultBackupRepo` | boolean | Yes | judge whether to set the backup is default which will be init |

