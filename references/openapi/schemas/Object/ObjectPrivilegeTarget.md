# ObjectPrivilegeTarget

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `objectType` | string | Yes | Native object kind returned by capabilities. Table includes views; view/foreignTable/materializedView also validate the concrete kind. |
| `databaseName` | string | No | Database name used to locate the resource. PostgreSQL also uses this as the connection database, including cluster-wide objects. |
| `schemaName` | string | No | Native schema containing the object, or the schema itself for schema objects. |
| `objectName` | string | No | Exact object name, never a SQL fragment. Required except for global, database, schema, and largeObject. |
| `objectId` | string | No | Opaque native identity returned by discovery. Interpretation and validation belong to the engine. PostgreSQL routines and large objects require a nonzero uint32 OID; routine names must also match. |
| `catalogName` | string | No | Native catalog name when required by engine capabilities. Unsupported fields are rejected. |

