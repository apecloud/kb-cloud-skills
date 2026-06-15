# TopicOffset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `topic` | string | No | 主题名称 |
| `partition` | integer (int32) | No | 分区号 |
| `consumerOffset` | integer (int64) | No | 消费者组当前消费位置 |
| `beginningOffset` | integer (int64) | No | 分区最早消息的偏移量 |
| `endOffset` | integer (int64) | No | 分区最新消息的下一个偏移量 |
| `groupId` | string | No | 消费者组ID |

