# ObjectPrivilegeChange

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `target` | [ObjectPrivilegeTarget](ObjectPrivilegeTarget.md) | Yes |  |
| `action` | string | Yes | Operation, either grant or revoke. |
| `privileges` | ObjectPrivilegeSpec[] | No | Required except when revoking MySQL scope-wide GRANT OPTION. Dynamic global privileges require explicit names. |
| `grantOption` | boolean | No | Grant delegation. MySQL static GRANT OPTION is scope-wide; dynamic global privileges each have their own grant option. |
| `grantOptionOnly` | boolean | No | Revoke delegation only. PostgreSQL applies to listed privileges. MySQL requires an empty privileges list and revokes GRANT OPTION at the entire scope; global dynamic grant options can also be removed. |
| `extensions` | object | No | Versioned namespaced JSON extensions. Response keys unknown to a client may be ignored. Change keys must be registered and strictly decoded by the current engine; PG/MySQL currently accept no change extensions. |
| `grantPrerequisites` | boolean | No | Explicitly grant advertised access prerequisites. PG schema-contained grants add CONNECT and schema USAGE in the same transaction; never sequence privileges. Defaults false; later revoke does not undo prerequisites. |
| `revokeBehavior` | string | No | Explicit native revoke behavior from capabilities; valid only for revoke. Omitted uses the advertised default. |

