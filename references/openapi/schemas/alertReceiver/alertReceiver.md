# alertReceiver

Alert receiver information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `createdAt` | string (date-time) | No |  |
| `id` | string | No |  |
| `name` | string | No |  |
| `category` | [alertReceiverCategory](alertReceiverCategory.md) | No |  |
| `updatedAt` | string (date-time) | No |  |
| `userGroup` | object | No |  |
| `webhookConfig` | [webhookConfig](webhookConfig.md) | No |  |
| `orgName` | string | No |  |

## Nested Fields

### `userGroup`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `emailEnabled` | boolean | No |  |
| `ids` | string[] | No |  |
| `smsEnabled` | boolean | No |  |

