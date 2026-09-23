# computeGroup

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups` | List compute groups | [View](../operations/listComputeGroups.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups` | Create compute group | [View](../operations/createComputeGroup.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}` | Get compute group | [View](../operations/getComputeGroup.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}` | Delete compute group | [View](../operations/deleteComputeGroup.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/scale` | Scale compute group | [View](../operations/scaleComputeGroup.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/start` | Start compute group | [View](../operations/startComputeGroup.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/stop` | Stop compute group | [View](../operations/stopComputeGroup.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts` | List compute group accounts | [View](../operations/listComputeGroupAccounts.md) |
| PUT | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts/{accountName}` | Grant compute group account | [View](../operations/grantComputeGroupAccount.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts/{accountName}` | Revoke compute group account | [View](../operations/revokeComputeGroupAccount.md) |
| PUT | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/computeGroups/{groupName}/accounts/{accountName}/default` | Set default compute group | [View](../operations/setDefaultComputeGroup.md) |
