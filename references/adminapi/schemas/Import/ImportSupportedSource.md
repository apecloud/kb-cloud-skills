# ImportSupportedSource

Supported data source definition for an import capability.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [ImportSourceType](ImportSourceType.md) | Yes |  |
| `category` | [ImportSourceCategory](ImportSourceCategory.md) | Yes |  |
| `name` | string | Yes | Display name of the supported source. |
| `supported` | boolean | Yes | Whether the source is currently supported. |
| `description` | [localizedDescription](localizedDescription.md) | No |  |
| `guide` | [localizedDescription](localizedDescription.md) | No |  |
| `capabilities` | ImportCapabilityType[] | No | Supported import capabilities. |
| `requirements` | localizedDescription[] | No | Prerequisite steps for enabling the source. |
| `connectionFields` | ImportConnectionField[] | Yes | Required connection parameters for the source. |
| `supportedVersions` | string[] | No | Compatible source version patterns. |
| `replicationMetadata` | [ImportReplicationMetadata](ImportReplicationMetadata.md) | No |  |

