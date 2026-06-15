# PATCH /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/privileges

**Resource:** [rdbms](../resources/rdbms.md)
**update account privileges**
**Operation ID:** `updateAccountPrivileges`

update account privileges for rdbms engine

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the Cluster |
| `accountName` | path | string | Yes | name of the account |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [privilegeList](../schemas/privilegeList/privilegeList.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when account privileges are updated successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

