# postgresqlSpaceAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `summary` | [postgresqlSpaceSummary](postgresqlSpaceSummary.md) | Yes |  |
| `storageOverview` | [postgresqlStorageOverview](postgresqlStorageOverview.md) | Yes |  |
| `databases` | postgresqlDatabaseSpace[] | Yes | Sizes of all connectable non-template databases in the PostgreSQL instance. |
| `selectedDatabase` | string | Yes | Database used for tables, indexes, and toastRelations in this response. |
| `tables` | postgresqlTableSpace[] | Yes | Top tables from selectedDatabase. |
| `indexes` | postgresqlIndexSpace[] | Yes | Top indexes from selectedDatabase. |
| `toastRelations` | postgresqlToastRelationSpace[] | Yes | Toast relations derived from selectedDatabase table space data. |
| `sources` | postgresqlSpaceSource[] | Yes |  |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. |

