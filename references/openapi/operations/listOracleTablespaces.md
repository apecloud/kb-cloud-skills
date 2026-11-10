# GET /api/v1/data/oracle/organizations/{orgName}/clusters/{clusterName}/tablespaces

**Resource:** [oracle](../resources/oracle.md)
**List Oracle tablespaces**
**Operation ID:** `listOracleTablespaces`

List tablespaces for a Oracle cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

Array of [OracleTablespace](../schemas/Oracle/OracleTablespace.md)

