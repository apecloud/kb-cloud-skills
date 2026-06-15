# TopicMessage

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topic` | string | No | 消息所属的主题 |
| `partition` | integer (int32) | No | 消息所在的分区号 |
| `offset` | integer (int64) | No | 消息在分区中的偏移量 |
| `timestamp` | integer (int64) | No | 消息的时间戳 |
| `key` | string | No | 消息的key |
| `value` | string | No | 消息的内容 |

