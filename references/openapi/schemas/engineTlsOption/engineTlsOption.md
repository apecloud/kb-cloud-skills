# engineTlsOption

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `clusterScope` | boolean | No | When true, all components in the cluster share the same TLS certificate.
The secret name is cluster-scoped instead of per-component.
Example: set to true for Redis sentinel where sentinel and redis must use the same TLS.
 |
| `supported` | boolean | Yes | Explicit opt-in: true means this engine supports TLS/SSL configuration; false means it does not.
If engineOption omits tls (or tls is null), TLS is not supported. Only engines with tls.supported === true advertise TLS.
 |
| `excludedVersions` | string[] | No | Only applies when supported is true. Version patterns (regular expressions, RE2 / Go regexp) for versions
that still do not support TLS. If omitted or empty while supported is true, all versions are treated as TLS-capable.
Example: ^8\.1\.3($|[.\-]) matches 8.1.3 and 8.1.3.* but not 8.1.30.
 |

