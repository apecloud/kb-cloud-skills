# DELETE /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/reset

**Resource:** [rdbms](../resources/rdbms.md)
**Clear explicit account privileges**
**Operation ID:** `resetAccountPrivileges`

MySQL clears direct privileges at every scope (including columns, routines, dynamic privileges and grant options), explicit role memberships and PROXY grants for one exact user/host. Rejects protected accounts and servers with mandatory roles before writing. Preview does not mutate. Execution re-reads current grants; concurrent new grants can be included. Statements are not atomic; on failure refresh and preview before retrying. Existing sessions follow MySQL privilege-cache semantics; this does not lock the account or terminate connections. PostgreSQL requires selected databaseNames or explicit allDatabases=true. Selected scope clears direct database/local/default ACLs only. It preserves global memberships, role attributes and privileges in other databases. Whole-account scope additionally clears memberships and elevated attributes. PUBLIC access remains. Object ownership prevents reset; RESTRICT protects dependent grants. Each database is transactional, but cross-database reset is not atomic. No objects are dropped or reassigned.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `subjectType` | query | ObjectPrivilegeSubjectType | No | Native subject kind; path account name identifies the subject. |
| `host` | query | string | No | Deprecated MySQL host alias. Prefer subjectQualifiers. Do not specify host in both. |
| `subjectQualifiers` | query | string | No | JSON identity qualifiers; MySQL host defaults to %. |
| `databaseNames` | query | string[] | No | PostgreSQL only; exact selected database names as repeated parameters. Mutually exclusive with allDatabases. |
| `allDatabases` | query | boolean | No | PostgreSQL whole-account reset requires explicit true; otherwise databaseNames must be nonempty. Selected scope preserves global memberships/attributes and privileges outside those databases. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Privileges cleared; account and password preserved |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

