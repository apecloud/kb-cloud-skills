# DmsImportRequest

the data of the import task

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `firstLineColumn` | boolean | No | whether the first line of the file is column name |
| `fieldsTerminalBy` | string | No | the delimiter of fields |
| `fieldNames` | string[] | No | the field names |
| `ignoreForeignKey` | boolean | No | whether ignore foreign key when import data or not |
| `fileType` | string | Yes |  |
| `file` | string (binary) | No | the data file, csv or other format |
| `tableName` | string | Yes | the target table name |
| `database` | string | Yes | the database of the specific table, required for the engine which don't need to specify database when create database, such as mysql |
| `skipNull` | boolean | No | whether skip the row which has null value when import data |

