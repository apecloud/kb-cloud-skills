# storageProvider

Storage Provider comprises specifications that provide guidance accessing remote storage.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Unique identifier for the storage provider |
| `name` | string | No | Name of the storage provider |
| `credential` | string[] | No | defines which parameters are credential fields |
| `schema` | object | No | the schema for the storage provider for creating a storage |
| `required` | string[] | No | defines which parameters are required |
| `displayName` | [storageDisplayName](storageDisplayName.md) | No |  |
| `isLocal` | boolean | No | defines whether the storage is local |

