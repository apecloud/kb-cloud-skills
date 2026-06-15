# clusterObjectStorageConfig

Specify the object storage config for cluster like starrocks

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `serviceRef` | [serviceRef](serviceRef.md) | Yes |  |
| `bucket` | string | Yes | the bucket name for the object storage |
| `usePathStyle` | boolean | No | whether the object storage is using path-style. If false, virtual host style will be used. |
| `region` | string | No | region to use. If using a s3-compatible service that does not require a region (like minio), leave it blank. |

