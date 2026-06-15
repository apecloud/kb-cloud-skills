# paramTplListItem

parameter template information

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `orgName` | string | No | Name of the organization |
| `createdAt` | string (date-time) | No | CreatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |
| `description` | string | Yes | Description of parameter template |
| `majorVersions` | string[] | Yes | Major versions of database engine, eg: 8.0, 8.1, 8.2 |
| `engine` | string | Yes | Name of database engine |
| `component` | string | Yes | Name of component |
| `name` | string | Yes | Name of parameter template. Name must be unique within an Org |
| `partition` | string | Yes | the template partition in listParamTpl request |
| `paramTplID` | string | Yes | id of parameter template |
| `updatedAt` | string (date-time) | No | UpdatedAt is a timestamp representing the server time when this object was created. It is not guaranteed to be set in happens-before order across separate operations. Clients may not set this value. It is represented in RFC3339 form and is in UTC.

Populated by the system. Read-only. Null for lists |

