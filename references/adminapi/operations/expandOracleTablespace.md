# PATCH /admin/v1/data/oracle/organizations/{orgName}/clusters/{clusterName}/tablespaces/{tablespaceName}

**Resource:** [oracle](../resources/oracle.md)
**Expand Oracle tablespace**
**Operation ID:** `expandOracleTablespace`

Expand one existing datafile/tempfile or add one file in the current container.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `tablespaceName` | path | string | Yes | Tablespace name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [OracleTablespaceExpand](../schemas/Oracle/OracleTablespaceExpand.md)

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

[OracleTablespace](../schemas/Oracle/OracleTablespace.md)

