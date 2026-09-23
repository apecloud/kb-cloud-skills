# DELETE /api/v1/data/clickhouse/organizations/{orgName}/clusters/{clusterName}/accounts/roles/{roleName}/privileges

**Resource:** [clickhouse](../resources/clickhouse.md)
**Revoke privileges from a ClickHouse role**
**Operation ID:** `revokeClickhouseRolePrivileges`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |
| `roleName` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema** (inline):

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `privileges` | object[] | Yes |  |

**`privileges` fields:**

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | string | No | The ON-clause operand of the grant, e.g. "db.*" or "*.*". |
| `privilege` | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Revoke ClickHouse role privileges successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

