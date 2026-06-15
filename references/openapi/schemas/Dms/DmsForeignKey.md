# DmsForeignKey

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The name of the foreign key |
| `columns` | string[] | No | The list of columns that make up the foreign key |
| `reference` | object | No | The reference details of the foreign key |
| `onUpdate` | string | No | The action on update (e.g., CASCADE, NO ACTION) |
| `onDelete` | string | No | The action on delete (e.g., CASCADE, NO ACTION) |

## Nested Fields

### `reference`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `database` | string | No | The referenced database |
| `schema` | string | No | The referenced schema |
| `table` | string | No | The referenced table |
| `columns` | string[] | No | The referenced columns |
| `matchType` | string | No | The match type for the foreign key (e.g., SIMPLE, FULL) |

