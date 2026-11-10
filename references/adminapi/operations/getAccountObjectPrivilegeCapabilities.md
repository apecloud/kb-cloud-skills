# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/capabilities

**Resource:** [rdbms](../resources/rdbms.md)
**List native object privilege capabilities for the connected server**
**Operation ID:** `getAccountObjectPrivilegeCapabilities`

Native object GRANT/REVOKE alongside presets. Consult capabilities for engine/version-specific object types and privileges. PostgreSQL RESTRICT is the default; MySQL static GRANT OPTION is scope-wide.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

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

[ObjectPrivilegeCapabilities](../schemas/Object/ObjectPrivilegeCapabilities.md)

