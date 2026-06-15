# resourceConstraint

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | resource constraint id |
| `engine` | string | Yes | engine name |
| `mode` | string | Yes | engine mode |
| `component` | string | Yes | engine component |
| `replicas` | [integerOption](integerOption.md) | No |  |
| `shards` | [integerOption](integerOption.md) | No |  |
| `volumes` | storageOption[] | No |  |

