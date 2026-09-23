# damengSpaceAnalysis

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `tablespaces` | damengTablespaceItem[] | Yes | Tablespace size and usage information from dba_free_space and dba_data_files. |
| `schemas` | damengSchemaItem[] | No | Schema-level size aggregation from DBA_SEGMENTS grouped by OWNER. |
| `tables` | damengTableSizeItem[] | No | Top-N tables ordered by total size from DBA_SEGMENTS (SEGMENT_TYPE='TABLE'). |
| `indexes` | damengIndexItem[] | No | Top-N indexes ordered by size from DBA_INDEXES joined with DBA_SEGMENTS. |

