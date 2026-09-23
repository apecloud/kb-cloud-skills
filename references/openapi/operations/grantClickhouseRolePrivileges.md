# POST /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}/privileges

**Resource:** [clickhouse](../resources/clickhouse.md)
**Grant privileges to a ClickHouse role**
**Operation ID:** `grantClickhouseRolePrivileges`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | string | No | The ON-clause operand of the grant, e.g. "db.*" or "*.*". |
| `privileges` | string[] | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Grant ClickHouse role privileges successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

