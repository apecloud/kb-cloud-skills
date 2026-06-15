# environmentEngineOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | record id |
| `engineName` | string | Yes | engine name |
| `mode` | string | Yes | engine mode |
| `networkModes` | string[] | Yes | network modes configured for this engine+mode+env combination |
| `envId` | string (uuid) | Yes | environment id |
| `envName` | string | Yes | environment name |
| `createTime` | string (date-time) | No | create time |
| `updateTime` | string (date-time) | No | update time |

