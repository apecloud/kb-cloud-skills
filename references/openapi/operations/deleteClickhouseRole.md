# DELETE /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}

**Resource:** [clickhouse](../resources/clickhouse.md)
**Delete a ClickHouse role**
**Operation ID:** `deleteClickhouseRole`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete ClickHouse role successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

