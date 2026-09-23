# GET /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/{accountName}/roles

**Resource:** [clickhouse](../resources/clickhouse.md)
**List the roles granted to a ClickHouse account**
**Operation ID:** `listClickhouseAccountRoles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `accountName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List ClickHouse account roles successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | The role name. |
| `privileges` | object[] | No | Privileges granted to the role, grouped by scope. |

**`privileges` fields:**

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | string | No | The ON-clause operand of the grant, e.g. "db.*" or "*.*". |
| `privileges` | string[] | No |  |

