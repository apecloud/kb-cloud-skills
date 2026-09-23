# RedisKeyValue

Discriminated Redis key value payload for string, hash, list, set, zset, stream, and json editors.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | Redis value type, such as string, hash, list, set, zset, stream, or json. |
| `text` | string | No | String or serialized scalar value for string/json previews. |
| `items` | RedisKeyValueItem[] | No | Paged collection items for hash, list, set, zset, stream, and json collection previews. |
| `cursor` | string | No | Cursor for the next value page. Empty or "0" means the value page is complete. |
| `offset` | integer (int64) | No | Offset used by offset-based value pagination. |
| `limit` | integer (int64) | No | Maximum number of value items returned. |
| `truncated` | boolean | No | Whether the returned value is truncated by size or item limit. |
| `jsonPath` | string | No | JSON path used for the returned JSON value. |

