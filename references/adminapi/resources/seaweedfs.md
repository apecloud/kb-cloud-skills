# seaweedfs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts` | listSeaweedFSAccounts | [View](../operations/listSeaweedFSAccounts.md) |
| POST | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts` | createSeaweedFSAccount | [View](../operations/createSeaweedFSAccount.md) |
| DELETE | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | deleteSeaweedFSAccount | [View](../operations/deleteSeaweedFSAccount.md) |
| PATCH | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | updateSeaweedFSAccount | [View](../operations/updateSeaweedFSAccount.md) |
| GET | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/root-password` | getRootSeaweedFSAccountPassword | [View](../operations/getRootSeaweedFSAccountPassword.md) |
| PATCH | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | updateSeaweedFSAccountPrivileges | [View](../operations/updateSeaweedFSAccountPrivileges.md) |
| GET | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies` | listSeaweedFSPolicies | [View](../operations/listSeaweedFSPolicies.md) |
| PUT | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}` | putSeaweedFSPolicy | [View](../operations/putSeaweedFSPolicy.md) |
| DELETE | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}` | deleteSeaweedFSPolicy | [View](../operations/deleteSeaweedFSPolicy.md) |
| PUT | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/policies` | bindSeaweedFSPolicies | [View](../operations/bindSeaweedFSPolicies.md) |
| POST | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys` | createSeaweedFSAccessKey | [View](../operations/createSeaweedFSAccessKey.md) |
| DELETE | `/admin/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys/{accessKey}` | deleteSeaweedFSAccessKey | [View](../operations/deleteSeaweedFSAccessKey.md) |
