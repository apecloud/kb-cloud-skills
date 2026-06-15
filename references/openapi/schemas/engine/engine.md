# engine

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | engine ID |
| `description` | string | No | the engine description |
| `name` | string | No | engine Name |
| `version` | string | No | engine version |
| `kbVersionConstraint` | string | No | KubeBlocks version constrain |
| `type` | string | No |  |
| `installed` | boolean | No | whether the engine is installed |
| `provider` | string | No | engine addon provider |
| `status` | [engineStatus](engineStatus.md) | No |  |
| `availableVersion` | string[] | No | engine available versions |
| `upgradeHistory` | string | No | engine upgrade history |
| `errMsg` | string | No | engine error messages when the engine status is failed |
| `clusterVersions` | string[] | No | clusterversion in the engines |
| `maturityLevel` | string | No | engine maturity level |

