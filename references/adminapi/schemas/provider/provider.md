# provider

The cloud provider that the environment is running on.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the cloud provider. |
| `nameCN` | string | Yes | The Chinese name of the cloud provider. |
| `nameEN` | string | Yes | The English name of the cloud provider. |
| `logo` | string | Yes | The logo of the cloud provider. |
| `enabled` | boolean | Yes | Whether the cloud provider is enabled. |
| `supportARN` | boolean | Yes | Whether the cloud provider supports ARN. |
| `environmentCount` | integer | Yes | The number of environments that the cloud provider has. |
| `regionCount` | integer | Yes | The number of regions that the cloud provider has. |
| `zoneCount` | integer | Yes | The number of zones that the cloud provider has. |
| `createdAt` | string (date-time) | Yes | The time when the cloud provider was created. |
| `updatedAt` | string (date-time) | Yes | The time when the cloud provider was last updated. |

