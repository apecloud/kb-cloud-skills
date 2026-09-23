# PATCH /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}

**Resource:** [clickhouse](../resources/clickhouse.md)
**Update a ClickHouse account password**
**Operation ID:** `updateClickhouseAccountPassword`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `password` | string | Yes | The new account password. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Update ClickHouse account password successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

