# dataCheckCreate

Exactly one entry point must be used. Provide channelID with checkType to create from an existing channel, or provide environmentID, project, source, target, replicationObjects, and checkType for direct creation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `checkType` | [dataCheckType](dataCheckType.md) | Yes |  |
| `channelID` | string | No | Existing data replication channel ID used only as a create-time shortcut. |
| `environmentID` | string | No | Environment UUID for direct check creation. |
| `project` | string | No | Kubernetes namespace for direct check creation. |
| `source` | [dataChannelEndpointCreate](dataChannelEndpointCreate.md) | No |  |
| `target` | [dataChannelEndpointCreate](dataChannelEndpointCreate.md) | No |  |
| `replicationObjects` | [dataChannelObject](dataChannelObject.md) | No |  |

