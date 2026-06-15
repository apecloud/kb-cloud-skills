# environmentCreate

Environment creation info

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The full, unique name of this Object in the format environments/{name}, set during creation. name must be a valid RFC 1123 compliant DNS label |
| `type` | [environmentType](environmentType.md) | Yes |  |
| `schedulingConfig` | [schedulingConfig](schedulingConfig.md) | No |  |
| `provisionConfig` | [provisionConfig](provisionConfig.md) | Yes |  |
| `organizations` | string[] | Yes | Organizations that have access for this environment |
| `provider` | string | Yes | Cloud Provider |
| `region` | string | Yes | Cloud Region |
| `availabilityZones` | string[] | No | Availability Zones |
| `description` | string | No | The description of the organization |
| `displayName` | string | Yes | The display name of the environment |
| `id` | string (uuid) | No |  |
| `extraInfo` | string | No | Extra info for environment |
| `deletePolicy` | [environmentDeletePolicy](environmentDeletePolicy.md) | No |  |
| `overwrite` | boolean | No | overwrite a environment if it has been added before |
| `dns` | [dns](dns.md) | No |  |
| `sla` | boolean | No | whether to enable calculate the cluster SLA for the environment |

