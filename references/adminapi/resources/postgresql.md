# postgresql

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions` | List PostgreSQL extensions | [View](../operations/listPGExtensions.md) |
| POST | `/admin/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions` | Enable PostgreSQL extensions in selected databases | [View](../operations/createPGExtension.md) |
| DELETE | `/admin/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions/{extensionName}` | drop PostgreSQL extension | [View](../operations/dropPGExtension.md) |
