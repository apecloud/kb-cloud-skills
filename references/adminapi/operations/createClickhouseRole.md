# POST /admin/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles

**Resource:** [clickhouse](../resources/clickhouse.md)
**Create a ClickHouse role with privileges**
**Operation ID:** `createClickhouseRole`

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
| `name` | string | No | The role name. |
| `privileges` | object[] | No | Privileges granted to the role, grouped by scope. |

**`privileges` fields:**

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | string | No | The ON-clause operand of the grant, e.g. "db.*" or "*.*". |
| `privileges` | string[] | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Create ClickHouse role successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

