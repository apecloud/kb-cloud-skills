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
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listAccounts.md) |
| POST | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createAccount.md) |
| DELETE | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteAccount.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateAccount.md) |
| GET | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/root-password` | get root account password | [View](../operations/getRootAccountPassword.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | update account privileges | [View](../operations/updateAccountPrivileges.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/lock` | Lock cluster account | [View](../operations/lockAccount.md) |
| PATCH | `/api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock` | Unlock cluster account | [View](../operations/unlockAccount.md) |
| GET | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | List mongodb accounts | [View](../operations/listMongoDBAccounts.md) |
| POST | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | Create mongodb account | [View](../operations/createMongoDBAccount.md) |
| DELETE | `/api/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete mongodb account | [View](../operations/deleteMongoDBAccount.md) |
| DELETE | `/api/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | delete mssql account compatible with windows account | [View](../operations/deleteMssqlAccount.md) |
| PATCH | `/api/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | update mssql account compatible with windows account | [View](../operations/updateMssqlAccount.md) |
| GET | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | List RabbitMQ accounts | [View](../operations/listRabbitAccounts.md) |
| POST | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | Create RabbitMQ account | [View](../operations/createRabbitAccount.md) |
| DELETE | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete RabbitMQ account | [View](../operations/deleteRabbitAccount.md) |
| PATCH | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update RabbitMQ account password | [View](../operations/updateRabbitAccountPassword.md) |
| PUT | `/api/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | Update RabbitMQ account privileges | [View](../operations/updateRabbitAccountPrivileges.md) |
