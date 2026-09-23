# GET /admin/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/privileges

**Resource:** [clickhouse](../resources/clickhouse.md)
**List privileges supported by the ClickHouse server**
**Operation ID:** `listClickhousePrivileges`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List ClickHouse privileges successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

