# mysqlSpaceAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `summary` | [mysqlSpaceSummary](mysqlSpaceSummary.md) | Yes |  |
| `storageOverview` | [mysqlStorageOverview](mysqlStorageOverview.md) | Yes |  |
| `databases` | mysqlDatabaseSpace[] | Yes | Sizes of all non-system MySQL databases. |
| `selectedDatabase` | string | Yes | Database used for table and index details. |
| `tables` | mysqlTableSpace[] | Yes | Top tables from selectedDatabase. |
| `indexes` | mysqlIndexSpace[] | Yes | Top indexes from selectedDatabase. Individual index size can be unavailable when mysql.innodb_index_stats is inaccessible. |
| `sources` | mysqlSpaceSource[] | Yes |  |
| `collectedAt` | string | Yes | Backend collection timestamp in UTC. |

