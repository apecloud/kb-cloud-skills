# ObjectPrivilegeCapability

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `objectType` | string | Yes |  |
| `privileges` | ObjectPrivilegeDefinition[] | Yes |  |
| `requiredTargetFields` | string[] | Yes |  |
| `warnings` | string[] | No |  |
| `requiredDiscoveryFields` | string[] | Yes | Fields required to enumerate objects of this kind; distinct from fields needed to identify an individual target. |
| `revokeGrantOptionScope` | [ObjectPrivilegeGrantOptionScope](ObjectPrivilegeGrantOptionScope.md) | No |  |
| `extensions` | object | No | Versioned namespaced JSON extensions. Response keys unknown to a client may be ignored. Change keys must be registered and strictly decoded by the current engine; PG/MySQL currently accept no change extensions. |
| `supportsGrantPrerequisites` | boolean | No | Allows explicitly granting the documented access prerequisites together with an object grant. |
| `grantPrerequisitesAtomic` | boolean | No | When prerequisite grants are supported, whether they and the requested grant are atomic. |
| `revokeBehaviors` | string[] | Yes | Explicit revoke behaviors supported by this object kind. Omitted change behavior uses defaultRevokeBehavior. |
| `defaultRevokeBehavior` | string | Yes | Default native revoke behavior. PostgreSQL restrict; MySQL native. |
| `changeExtensions` | string[] | No | Versioned namespaces accepted for change extensions by this engine/version; empty means none. |

