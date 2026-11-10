# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges

**Resource:** [rdbms](../resources/rdbms.md)
**Inspect native object and column privileges**
**Operation ID:** `getAccountObjectPrivileges`

Native object GRANT/REVOKE alongside presets. Consult capabilities for engine/version-specific object types and privileges. PostgreSQL RESTRICT is the default; MySQL static GRANT OPTION is scope-wide.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `objectType` | query | string | Yes |  |
| `databaseName` | query | string | No |  |
| `schemaName` | query | string | No |  |
| `objectName` | query | string | No |  |
| `objectId` | query | string | No |  |
| `subjectType` | query | ObjectPrivilegeSubjectType | No | Native subject kind; path account name identifies the subject. |
| `host` | query | string | No | Deprecated MySQL host alias. Prefer subjectQualifiers. Do not specify host in both. |
| `catalogName` | query | string | No |  |
| `subjectQualifiers` | query | string | No | JSON object of string identity qualifiers, e.g. {"host":"%"}. Allowed keys and defaults come from capabilities. Unknown keys or duplicate identity inputs are rejected. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Native privilege snapshot |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[ObjectPrivilegeSnapshot](../schemas/Object/ObjectPrivilegeSnapshot.md)

