# elasticsearchIndexStorage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `uuid` | string | No |  |
| `health` | string | Yes |  |
| `status` | string | Yes |  |
| `primaryShards` | integer (int64) | Yes |  |
| `replicaShards` | integer (int64) | Yes |  |
| `documents` | integer (int64) | Yes |  |
| `deletedDocuments` | integer (int64) | Yes |  |
| `primaryStoreBytes` | integer (int64) | Yes |  |
| `totalStoreBytes` | integer (int64) | Yes |  |
| `segments` | integer (int64) | Yes |  |

