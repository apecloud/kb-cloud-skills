# environmentModule

Single environment module information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | Environment module name |
| `version` | string | No | Environment module version |
| `status` | [environmentModuleStatus](environmentModuleStatus.md) | Yes |  |
| `replicas` | integer | No | Number of replicas |
| `location` | string | No | Deployment location |
| `clusterInfo` | [clusterInfo](clusterInfo.md) | No |  |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `displayName` | [localizedDescription](localizedDescription.md) | No |  |
| `optional` | boolean | No | indicate module is optional. If false, the module is required and must be installed |
| `defaultEnabled` | boolean | No | indicate whether module is enabled by default when creating environment. Only effective when optional is true |

