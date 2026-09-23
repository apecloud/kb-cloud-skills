# GET /admin/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles

**Resource:** [clickhouse](../resources/clickhouse.md)
**List ClickHouse roles**
**Operation ID:** `listClickhouseRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `forCreateUser` | query | boolean | No | Whether to include built-in privilege roles for creating an account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List ClickHouse roles successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

