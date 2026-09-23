# GET /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [clickhouse](../resources/clickhouse.md)
**Get the grants (privileges) of a ClickHouse role**
**Operation ID:** `getClickhouseRoleGrants`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get ClickHouse role grants successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

