# GET /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topic/{topic}/messages

**Resource:** [kafka](../resources/kafka.md)
**List messages from topic**
**Operation ID:** `listKafkaTopicMessages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |
| `topic` | path | string | Yes |  |
| `partition` | query | integer | Yes |  |
| `offset` | query | integer | Yes |  |
| `count` | query | integer | No | 获取消息的数量 |
| `keyFilter` | query | string | No | 消息 key 的过滤条件（大小写不敏感） |
| `valueFilter` | query | string | No | 消息内容的过滤条件（大小写不敏感） |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[TopicMessageList](../schemas/Topic/TopicMessageList.md)

