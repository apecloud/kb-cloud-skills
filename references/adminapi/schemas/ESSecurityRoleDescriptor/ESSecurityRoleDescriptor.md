# ESSecurityRoleDescriptor

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |
| `cluster` | string[] | No |  |
| `global` | object | No |  |
| `indices` | ESSecurityIndexPrivileges[] | No |  |
| `remote_indices` | ESSecurityRemoteIndexPrivileges[] | No |  |
| `remote_cluster` | ESSecurityRemoteClusterPrivileges[] | No |  |
| `applications` | ESSecurityApplicationPrivileges[] | No |  |
| `run_as` | string[] | No |  |
| `metadata` | object | No |  |
| `restriction` | object | No |  |
| `transient_metadata` | object | No |  |

