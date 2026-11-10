# account

Cluster Account APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts` | InfluxDB ListUsers | [View](../operations/influxDBListUsers.md) |
| POST | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts` | InfluxDB CreateUser | [View](../operations/influxDBCreateUser.md) |
| DELETE | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}` | InfluxDB DeleteUser | [View](../operations/influxDBDeleteUser.md) |
| PATCH | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/password` | InfluxDB ChangePassword | [View](../operations/influxDBChangePassword.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/organizations` | InfluxDB ListOrganizations | [View](../operations/influxDBListOrganizations.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/buckets` | InfluxDB ListBuckets | [View](../operations/influxDBListBuckets.md) |
| GET | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens` | InfluxDB ListTokens | [View](../operations/influxDBListTokens.md) |
| POST | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens` | InfluxDB CreateToken | [View](../operations/influxDBCreateToken.md) |
| DELETE | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens/{tokenID}` | InfluxDB DeleteToken | [View](../operations/influxDBDeleteToken.md) |
| PATCH | `/api/v1/data/influxdb/organizations/{orgName}/clusters/{clusterName}/accounts/{userID}/tokens/{tokenID}` | InfluxDB UpdateToken | [View](../operations/influxDBUpdateToken.md) |
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
| GET | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listKafkaAccounts.md) |
| POST | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createKafkaAccount.md) |
| DELETE | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteKafkaAccount.md) |
| PATCH | `/api/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateKafkaAccount.md) |
| GET | `/api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts` | Get Hive accounts | [View](../operations/getHiveAccounts.md) |
| POST | `/api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts` | Create Hive account | [View](../operations/createHiveAccount.md) |
| DELETE | `/api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete hive account | [View](../operations/deleteHiveAccount.md) |
| PATCH | `/api/v1/data/hive/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update hive account | [View](../operations/updateHiveAccount.md) |
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
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listAccounts.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createAccount.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteAccount.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateAccount.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/root-password` | get root account password | [View](../operations/getRootAccountPassword.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges` | Inspect native object and column privileges | [View](../operations/getAccountObjectPrivileges.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges` | Grant or revoke native object and column privileges | [View](../operations/changeAccountObjectPrivileges.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/capabilities` | List native object privilege capabilities for the connected server | [View](../operations/getAccountObjectPrivilegeCapabilities.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/overview` | Read native account privilege summary or selected database evidence | [View](../operations/getAccountPrivilegeOverview.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/reset` | Preview clearing explicit account privileges | [View](../operations/previewAccountPrivilegeReset.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/reset` | Clear explicit account privileges | [View](../operations/resetAccountPrivileges.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/columns` | List exact column names for account object privileges | [View](../operations/listAccountObjectPrivilegeColumns.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/object-privileges/objects` | Discover existing native privilege objects with stable routine identities | [View](../operations/listAccountObjectPrivilegeObjects.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | update account privileges | [View](../operations/updateAccountPrivileges.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/lock` | Lock cluster account | [View](../operations/lockAccount.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock` | Unlock cluster account | [View](../operations/unlockAccount.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys` | List MinIO access keys | [View](../operations/listServiceAccounts.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys` | Create MinIO access key | [View](../operations/createServiceAccount.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys/{accessKey}` | Get MinIO access key | [View](../operations/getServiceAccount.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys/{accessKey}` | Delete MinIO access key | [View](../operations/deleteServiceAccount.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys/{accessKey}` | Update MinIO access key | [View](../operations/updateServiceAccount.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | List mongodb accounts | [View](../operations/listMongoDBAccounts.md) |
| POST | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | Create mongodb account | [View](../operations/createMongoDBAccount.md) |
| DELETE | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete mongodb account | [View](../operations/deleteMongoDBAccount.md) |
| GET | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles` | List Milvus roles | [View](../operations/listMilvusRoles.md) |
| POST | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles` | Create Milvus role | [View](../operations/createMilvusRole.md) |
| GET | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Get Milvus role | [View](../operations/getMilvusRole.md) |
| PUT | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Update Milvus role | [View](../operations/updateMilvusRole.md) |
| DELETE | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Delete Milvus role | [View](../operations/deleteMilvusRole.md) |
| PATCH | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update Milvus account password | [View](../operations/updateMilvusAccountPassword.md) |
| PUT | `/api/v1/data/milvus/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles` | Update Milvus account roles | [View](../operations/updateMilvusAccountRoles.md) |
| DELETE | `/api/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | delete mssql account compatible with windows account | [View](../operations/deleteMssqlAccount.md) |
| PATCH | `/api/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | update mssql account compatible with windows account | [View](../operations/updateMssqlAccount.md) |
| GET | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | List RabbitMQ accounts | [View](../operations/listRabbitAccounts.md) |
| POST | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | Create RabbitMQ account | [View](../operations/createRabbitAccount.md) |
| DELETE | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete RabbitMQ account | [View](../operations/deleteRabbitAccount.md) |
| PATCH | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update RabbitMQ account password | [View](../operations/updateRabbitAccountPassword.md) |
| PUT | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | Update RabbitMQ account privileges | [View](../operations/updateRabbitAccountPrivileges.md) |
