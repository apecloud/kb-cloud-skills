# storage

Storage is a specification that provides guidance accessing remote storage.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | Unique identifier for the storage |
| `name` | string | No | Name of the storage |
| `storageProvider` | string | No | Name of the storage provider |
| `params` | object | No | the parameters for the storage |
| `envName` | string | No | the environment name that storage belongs to |
| `createdBy` | string (date-time) | No | User who created the storage |
| `clusterID` | string | No | the id of cluster that storage used |
| `clusterMetadataAddress` | string | No | the address of cluster |
| `updatedBy` | string (date-time) | No | User who updated the storage |
| `tags` | object | No | the tags for the storage |

