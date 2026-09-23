# account

Cluster Account APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
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
