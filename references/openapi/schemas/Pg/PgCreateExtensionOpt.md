# PgCreateExtensionOpt

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `databases` | string[] | Yes | Target databases. At most 100 database-extension pairs per request. |
| `names` | string[] | Yes | Extensions to enable using their default versions and schemas. |
| `version` | string | No | The version of the extension to install. |
| `schema` | string | No | The schema where the extension is installed. |

