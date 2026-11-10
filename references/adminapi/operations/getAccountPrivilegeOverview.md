# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/overview

**Resource:** [rdbms](../resources/rdbms.md)
**Read native account privilege summary or selected database evidence**
**Operation ID:** `getAccountPrivilegeOverview`

Without databaseName, returns role attributes, memberships, database access summaries and shared ACLs without connecting to other databases. PostgreSQL databaseName reads schema, object, ownership and PUBLIC evidence from that database only. Failed reads return an error, never an empty grant list. SQL is read-only evidence, not an exhaustive effective-access decision.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes |  |
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |
| `subjectType` | query | ObjectPrivilegeSubjectType | No | Native subject kind; path account name identifies the subject. |
| `host` | query | string | No | Deprecated MySQL host alias. Prefer subjectQualifiers. Do not specify host in both. |
| `subjectQualifiers` | query | string | No |  |
| `databaseName` | query | string | No | PostgreSQL database to inspect on demand. Omit for the global summary. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Native evidence groups for the requested scope |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [ObjectPrivilegeEvidence](../schemas/Object/ObjectPrivilegeEvidence.md)

