# DELETE /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [clickhouse](../resources/clickhouse.md)
**Delete a ClickHouse account**
**Operation ID:** `deleteClickhouseAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Delete ClickHouse account successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

