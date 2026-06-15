# PgExtensionAvailableDatabaseSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | The database where the extension can be installed. |
| `schemas` | string[] | No | The schema candidates or fixed schema hints for this extension in the database. Extensions with fixed schemas return schemas declared by extension metadata. Relocatable extensions return current database schemas as install candidates. Non-relocatable extensions without fixed schema hints only return the public schema when it exists. |

