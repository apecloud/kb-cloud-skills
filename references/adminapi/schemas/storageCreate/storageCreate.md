# storageCreate

storageCreate is the schema for the storage create request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the storage |
| `storageProvider` | string | Yes | Name of the storage provider |
| `params` | object | No | the parameters to create the storage |
| `clusterID` | string | No | the id of cluster that storage used |
| `tags` | object | No | the tags for the storage |

