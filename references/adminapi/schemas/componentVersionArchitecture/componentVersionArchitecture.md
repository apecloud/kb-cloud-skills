# componentVersionArchitecture

Architecture support configuration for this component versions.
If not set, the component versions support all architectures.


**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amd64` | string[] | No | List of versions that support amd64 architecture.
Supports version patterns: exact version "8.0.33", major version "8.0", version range ">=8.0.30", etc.
If not set, all versions support amd64.
 |
| `arm64` | string[] | No | List of versions that support arm64 architecture.
Supports version patterns: exact version "8.0.33", major version "8.0", version range ">=8.0.30", etc.
If not set, all versions support arm64.
 |

