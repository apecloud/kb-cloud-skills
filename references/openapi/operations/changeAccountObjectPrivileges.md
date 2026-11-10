# PATCH /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges

**Resource:** [rdbms](../resources/rdbms.md)
**Grant or revoke native object and column privileges**
**Operation ID:** `changeAccountObjectPrivileges`

Native object GRANT/REVOKE alongside presets. Consult capabilities for engine/version-specific object types and privileges. PostgreSQL RESTRICT is the default; MySQL static GRANT OPTION is scope-wide.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `subjectType` | query | ObjectPrivilegeSubjectType | No | Native subject kind; path account name identifies the subject. |
| `host` | query | string | No | Deprecated MySQL host alias. Prefer subjectQualifiers. Do not specify host in both. |
| `subjectQualifiers` | query | string | No | JSON object of string identity qualifiers, e.g. {"host":"%"}. Allowed keys and defaults come from capabilities. Unknown keys or duplicate identity inputs are rejected. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ObjectPrivilegeChange](../schemas/Object/ObjectPrivilegeChange.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Native statement completed. Query privileges again to inspect remaining access. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 500 | (reference) |

