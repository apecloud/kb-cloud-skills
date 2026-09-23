# seaweedfs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts` | listSeaweedFSAccounts | [View](../operations/listSeaweedFSAccounts.md) |
| POST | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts` | createSeaweedFSAccount | [View](../operations/createSeaweedFSAccount.md) |
| DELETE | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | deleteSeaweedFSAccount | [View](../operations/deleteSeaweedFSAccount.md) |
| PATCH | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | updateSeaweedFSAccount | [View](../operations/updateSeaweedFSAccount.md) |
| GET | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/root-password` | getRootSeaweedFSAccountPassword | [View](../operations/getRootSeaweedFSAccountPassword.md) |
| PATCH | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | updateSeaweedFSAccountPrivileges | [View](../operations/updateSeaweedFSAccountPrivileges.md) |
| GET | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies` | listSeaweedFSPolicies | [View](../operations/listSeaweedFSPolicies.md) |
| PUT | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}` | putSeaweedFSPolicy | [View](../operations/putSeaweedFSPolicy.md) |
| DELETE | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/policies/{policyName}` | deleteSeaweedFSPolicy | [View](../operations/deleteSeaweedFSPolicy.md) |
| PUT | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/policies` | bindSeaweedFSPolicies | [View](../operations/bindSeaweedFSPolicies.md) |
| POST | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys` | createSeaweedFSAccessKey | [View](../operations/createSeaweedFSAccessKey.md) |
| DELETE | `/api/v1/data/seaweedfs/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/access-keys/{accessKey}` | deleteSeaweedFSAccessKey | [View](../operations/deleteSeaweedFSAccessKey.md) |
