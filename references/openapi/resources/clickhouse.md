# clickhouse

ClickHouse Account and Privilege Management APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts` | List ClickHouse accounts | [View](../operations/listClickhouseAccounts.md) |
| POST | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts` | Create a ClickHouse account with optional roles | [View](../operations/createClickhouseAccount.md) |
| DELETE | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Delete a ClickHouse account | [View](../operations/deleteClickhouseAccount.md) |
| PATCH | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}` | Update a ClickHouse account password | [View](../operations/updateClickhouseAccountPassword.md) |
| GET | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles` | List the roles granted to a ClickHouse account | [View](../operations/listClickhouseAccountRoles.md) |
| PUT | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles` | Update the roles granted to a ClickHouse account | [View](../operations/updateClickhouseAccountRoles.md) |
| GET | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles` | List ClickHouse roles | [View](../operations/listClickhouseRoles.md) |
| POST | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles` | Create a ClickHouse role with privileges | [View](../operations/createClickhouseRole.md) |
| GET | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Get the grants (privileges) of a ClickHouse role | [View](../operations/getClickhouseRoleGrants.md) |
| DELETE | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}` | Delete a ClickHouse role | [View](../operations/deleteClickhouseRole.md) |
| POST | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}/privileges` | Grant privileges to a ClickHouse role | [View](../operations/grantClickhouseRolePrivileges.md) |
| DELETE | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}/privileges` | Revoke privileges from a ClickHouse role | [View](../operations/revokeClickhouseRolePrivileges.md) |
| GET | `/api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/privileges` | List privileges supported by the ClickHouse server | [View](../operations/listClickhousePrivileges.md) |
