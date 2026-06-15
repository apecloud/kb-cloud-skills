# RbmqVHost

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Virtual host name |
| `description` | string | No | Virtual host description |
| `tags` | string[] | No |  |
| `default_queue_type` | string | No | Type of queue to create in virtual host when unspecified |
| `tracing` | boolean | No | True if tracing is enabled for this virtual host |
| `messages` | integer | No | Total number of messages in queues of this virtual host |
| `messages_rate` | number (double) | No | Rate of messages in queues of this virtual host per second |
| `messages_ready` | integer | No | Total number of messages ready to be delivered in queues of this virtual host |
| `messages_ready_rate` | number (double) | No | Rate of messages ready to be delivered in queues of this virtual host per second |
| `messages_unacknowledged` | integer | No | Total number of messages pending acknowledgement from consumers in this virtual host |
| `messages_unacknowledged_rate` | number (double) | No | Rate of messages pending acknowledgement from consumers in this virtual host per second |
| `recv_oct` | integer (int64) | No | Octets received |
| `send_oct` | integer (int64) | No | Octets sent |
| `recv_cnt` | integer (int64) | No | Count of received messages |
| `send_cnt` | integer (int64) | No | Count of sent messages |
| `send_pend` | integer (int64) | No | Count of pending messages to be sent |
| `recv_oct_rate` | number (double) | No | Rate of octets received per second |
| `send_oct_rate` | number (double) | No | Rate of octets sent per second |

