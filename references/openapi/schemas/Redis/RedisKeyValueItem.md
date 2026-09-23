# RedisKeyValueItem

Stable Redis collection item shape. Fields are populated according to Redis value type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `field` | string | No | Hash field name. |
| `value` | any | No | Hash/list/set/json item value. The value may be a scalar, array, or object depending on Redis value type. |
| `member` | string | No | Set or sorted-set member. |
| `score` | number (double) | No | Sorted-set score. |
| `id` | string | No | Stream entry ID. |
| `fields` | object | No | Stream entry field/value map. |
| `index` | integer (int64) | No | List item index when available. |

