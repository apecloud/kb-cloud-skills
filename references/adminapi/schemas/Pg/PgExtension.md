# PgExtension

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the PostgreSQL extension. |
| `database` | string | No | The database where the extension is installed. |
| `default_version` | string | No | The default version of the extension. |
| `installed_version` | string | No | The currently installed version of the extension. |
| `schema` | string | No | The schema where the extension is installed. |
| `available_database_schema` | PgExtensionAvailableDatabaseSchema[] | No | The databases and schemas where the extension can be installed. This is empty for installed extensions. |
| `category` | string | No | The category of the extension. |
| `need_restart` | boolean | No | Whether the extension needs a restart to take effect. |
| `pg_version` | string[] | No | The version of PostgreSQL that the extension is compatible with. |
| `description_zn` | string | No | A description of the extension in Chinese. |
| `description_en` | string | No | A description of the extension in English. |

