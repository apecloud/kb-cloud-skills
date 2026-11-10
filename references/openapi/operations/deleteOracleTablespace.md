# DELETE /api/v1/data/oracle/organizations/{orgName}/clusters/{clusterName}/tablespaces/{tablespaceName}

**Resource:** [oracle](../resources/oracle.md)
**Delete Oracle tablespace**
**Operation ID:** `deleteOracleTablespace`

Delete tablespace for a Oracle cluster.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | Cluster name |
| `tablespaceName` | path | string | Yes | Tablespace name |
| `includingContents` | query | boolean | No | Explicitly delete all objects in the tablespace. Without this flag Oracle rejects nonempty tablespaces. |
| `deleteDatafiles` | query | boolean | No | Also remove physical files. Requires includingContents. Otherwise manually managed files are retained. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | A successful response. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

