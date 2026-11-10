# dolphindb

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/drain-preview` | Preview DolphinDB data node evacuation | [View](../operations/dolphinDBPreviewDrain.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/preview` | DolphinDB PreviewRebalance | [View](../operations/dolphinDBPreviewRebalance.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/distribution` | DolphinDB GetDistribution | [View](../operations/dolphinDBGetDistribution.md) |
| POST | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/rebalance/operations` | DolphinDB CreateRebalance | [View](../operations/dolphinDBCreateRebalance.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts` | DolphinDB ListUsers | [View](../operations/dolphinDBListUsers.md) |
| POST | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts` | DolphinDB CreateUser | [View](../operations/dolphinDBCreateUser.md) |
| DELETE | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | DolphinDB DeleteUser | [View](../operations/dolphinDBDeleteUser.md) |
| PATCH | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/password` | DolphinDB ChangePassword | [View](../operations/dolphinDBChangePassword.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups` | DolphinDB ListGroups | [View](../operations/dolphinDBListGroups.md) |
| POST | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups` | DolphinDB CreateGroup | [View](../operations/dolphinDBCreateGroup.md) |
| DELETE | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups/{groupName}` | DolphinDB DeleteGroup | [View](../operations/dolphinDBDeleteGroup.md) |
| PATCH | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/groups/{groupName}/members` | DolphinDB ChangeGroupMembers | [View](../operations/dolphinDBChangeGroupMembers.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/capabilities` | DolphinDB GetCapabilities | [View](../operations/dolphinDBGetCapabilities.md) |
| GET | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/{subjectType}/{subjectName}` | DolphinDB GetPermissions | [View](../operations/dolphinDBGetPermissions.md) |
| PATCH | `/api/v1/data/dolphindb/organizations/{orgName}/clusters/{clusterName}/privileges/{subjectType}/{subjectName}` | DolphinDB ChangePermissions | [View](../operations/dolphinDBChangePermissions.md) |
