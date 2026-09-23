# GET /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [clickhouse](../resources/clickhouse.md)
**List ClickHouse accounts**
**Operation ID:** `listClickhouseAccounts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List ClickHouse accounts successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[CkAccount](../schemas/Ck/CkAccount.md)

