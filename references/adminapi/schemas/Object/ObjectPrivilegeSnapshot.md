# ObjectPrivilegeSnapshot

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | [ObjectPrivilegeTarget](ObjectPrivilegeTarget.md) | Yes |  |
| `supportedPrivileges` | string[] | Yes |  |
| `supportedColumnPrivileges` | string[] | Yes |  |
| `directPrivileges` | ObjectPrivilegeGrant[] | Yes | Native grants to this account at this exact object scope. Does not include inherited grants or prove executable access. |
| `effectivePrivilegesKnown` | boolean | Yes | Native PostgreSQL checks when available. False for PostgreSQL large objects before 18 and MySQL (active roles depend on the session). False or omitted effectivePrivileges never means no access. |
| `effectivePrivileges` | ObjectPrivilegeGrant[] | No | PostgreSQL native has_*_privilege checks, including PUBLIC and inherited permissions. Other prerequisites, RLS and session SET ROLE can affect actual execution. |
| `warnings` | string[] | No | Native behavior and scope overlap explanations, including preset overlap and partial revokes. |
| `subject` | [ObjectPrivilegeSubject](ObjectPrivilegeSubject.md) | Yes |  |
| `extensions` | object | No | Versioned namespaced JSON extensions. Response keys unknown to a client may be ignored. Change keys must be registered and strictly decoded by the current engine; PG/MySQL currently accept no change extensions. |
| `prerequisiteChecks` | ObjectPrivilegePrerequisiteCheck[] | No |  |
| `evidence` | ObjectPrivilegeEvidence[] | No |  |

