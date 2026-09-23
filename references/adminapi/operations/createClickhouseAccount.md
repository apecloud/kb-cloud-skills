# POST /admin/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts

**Resource:** [clickhouse](../resources/clickhouse.md)
**Create a ClickHouse account with optional roles**
**Operation ID:** `createClickhouseAccount`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The account (user) name. |
| `password` | string | Yes | The account password. |
| `roles` | string[] | No | Roles to grant to the account on creation. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Create ClickHouse account successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

