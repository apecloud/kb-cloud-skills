# TopicMessageRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `partition` | integer (int32) | No | 指定消息将被发送到的Kafka分区 |
| `key` | string | No | 消息的键（可选） |
| `value` | string | No | 消息的实际内容 |

