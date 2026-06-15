# DmsTableMetadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the table |
| `schema` | string | No | The schema of the table |
| `database` | string | No | The database where the table resides |
| `comment` | string | No | A comment describing the table |
| `columns` | DmsTableColumn[] | No | List of columns in the table |
| `indexes` | DmsTableIndex[] | No | List of indexes on the table |
| `primaryKey` | [DmsPrimaryKey](DmsPrimaryKey.md) | No |  |
| `foreignKeys` | DmsForeignKey[] | No | List of foreign keys on the table |
| `uniqueKeys` | DmsUniqueKey[] | No | List of unique keys on the table |
| `checkConstraints` | DmsCheckConstraint[] | No | List of check constraints on the table |
| `excludeConstraints` | DmsExcludeConstraint[] | No | List of exclude constraints on the table |
| `partitioning` | [DmsTablePartitioning](DmsTablePartitioning.md) | No |  |
| `options` | [DmsTableOptions](DmsTableOptions.md) | No |  |

