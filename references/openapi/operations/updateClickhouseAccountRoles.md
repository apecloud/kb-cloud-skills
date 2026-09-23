# PUT /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles

**Resource:** [clickhouse](../resources/clickhouse.md)
**Update the roles granted to a ClickHouse account**
**Operation ID:** `updateClickhouseAccountRoles`

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
| `roles` | string[] | Yes | The full set of roles to grant to the account. Existing roles are replaced. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Update ClickHouse account roles successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

