# mongodb

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PUT | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users/{database}/{username}/password` | ChangeRBACUserPassword | [View](../operations/mongoChangeRBACUserPassword.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users` | ListRBACUsers | [View](../operations/mongoListRBACUsers.md) |
| POST | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users` | CreateRBACUser | [View](../operations/mongoCreateRBACUser.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/databases` | List MongoDB cluster databases | [View](../operations/mongoListClusterDatabases.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/databases/{database}/collections` | List MongoDB cluster database objects | [View](../operations/mongoListClusterCollections.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/capabilities` | GetRBACCapabilities | [View](../operations/mongoGetRBACCapabilities.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles` | ListRBACRoles | [View](../operations/mongoListRBACRoles.md) |
| POST | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles` | CreateRBACRole | [View](../operations/mongoCreateRBACRole.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles/{database}/{roleName}` | GetRBACRole | [View](../operations/mongoGetRBACRole.md) |
| PUT | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles/{database}/{roleName}` | UpdateRBACRole | [View](../operations/mongoUpdateRBACRole.md) |
| DELETE | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/roles/{database}/{roleName}` | DeleteRBACRole | [View](../operations/mongoDeleteRBACRole.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users/{database}/{username}` | GetRBACUser | [View](../operations/mongoGetRBACUser.md) |
| DELETE | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users/{database}/{username}` | DeleteRBACUser | [View](../operations/mongoDeleteRBACUser.md) |
| PATCH | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/rbac/users/{database}/{username}/roles` | ChangeRBACUserRoles | [View](../operations/mongoChangeRBACUserRoles.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | List mongodb accounts | [View](../operations/listMongoDBAccounts.md) |
| POST | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | Create mongodb account | [View](../operations/createMongoDBAccount.md) |
| DELETE | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete mongodb account | [View](../operations/deleteMongoDBAccount.md) |
