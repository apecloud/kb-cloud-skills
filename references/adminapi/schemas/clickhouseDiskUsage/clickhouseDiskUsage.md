# clickhouseDiskUsage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `diskName` | string | No | ClickHouse disk name. |
| `hostName` | string | No | ClickHouse server host. |
| `bytesOnDisk` | integer (int64) | No | bytes_on_disk for this disk and host. |
| `dataCompressedBytes` | integer (int64) | No | data_compressed_bytes for this disk and host. |
| `dataUncompressedBytes` | integer (int64) | No | data_uncompressed_bytes for this disk and host. |
| `rows` | integer (int64) | No | Rows on this disk and host. |
| `activeParts` | integer (int64) | No | Active parts on this disk and host. |

