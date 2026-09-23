# dataCheckDetailItem

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | No | Struct check object key. Present for struct details; omitted for snapshot row details. |
| `schema` | string | No | Source schema or database from the requested detail scope. |
| `tb` | string | No | Source table from the requested detail scope. |
| `target_schema` | string | No | Target schema or database for snapshot details when routing changes the target object. |
| `target_tb` | string | No | Target table for snapshot details when routing changes the target object. |
| `id_col_values` | object | No |  |
| `src_sql` | string | No |  |
| `diff_col_values` | object | No |  |
| `src_row` | object | No |  |
| `dst_row` | object | No |  |
| `dst_sql` | string | No |  |

