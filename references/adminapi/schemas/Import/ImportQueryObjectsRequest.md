# ImportQueryObjectsRequest

Request payload for querying import data source objects.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sourceType` | [ImportSourceType](ImportSourceType.md) | Yes |  |
| `connectionConfig` | object | Yes | Connection configuration parameters that vary by data source type. |
| `nodeType` | string | No | Current node type in the replication object tree. |
| `nodeValue` | string | No | Encoded node value of the current tree node. |
| `queryNodeType` | string | No | Target node type to enumerate for the next level. |

