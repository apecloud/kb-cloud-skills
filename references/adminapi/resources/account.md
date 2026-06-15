# account

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | List RabbitMQ accounts | [View](../operations/listRabbitAccounts.md) |
| POST | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts` | Create RabbitMQ account | [View](../operations/createRabbitAccount.md) |
| DELETE | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete RabbitMQ account | [View](../operations/deleteRabbitAccount.md) |
| PATCH | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update RabbitMQ account password | [View](../operations/updateRabbitAccountPassword.md) |
| PUT | `/admin/v1/data/rabbitmq/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | Update RabbitMQ account privileges | [View](../operations/updateRabbitAccountPrivileges.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | List cluster accounts | [View](../operations/listAccounts.md) |
| POST | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts` | Create cluster account | [View](../operations/createAccount.md) |
| DELETE | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete cluster account | [View](../operations/deleteAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | update cluster account | [View](../operations/updateAccount.md) |
| GET | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/root-password` | get root account password | [View](../operations/getRootAccountPassword.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges` | update account privileges | [View](../operations/updateAccountPrivileges.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/lock` | Lock cluster account | [View](../operations/lockAccount.md) |
| PATCH | `/admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/unlock` | Unlock cluster account | [View](../operations/unlockAccount.md) |
| GET | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | List mongodb accounts | [View](../operations/listMongoDBAccounts.md) |
| POST | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts` | Create mongodb account | [View](../operations/createMongoDBAccount.md) |
| DELETE | `/admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete mongodb account | [View](../operations/deleteMongoDBAccount.md) |
| DELETE | `/admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | delete mssql account compatible with windows account | [View](../operations/deleteMssqlAccount.md) |
| PATCH | `/admin/v1/data/mssql/organizations/{orgName}/clusters/{clusterName}/accounts` | update mssql account compatible with windows account | [View](../operations/updateMssqlAccount.md) |
