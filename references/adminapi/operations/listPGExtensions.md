# GET /admin/v1/data/postgresql/organizations/{orgName}/clusters/{clusterName}/extensions

**Resource:** [postgresql](../resources/postgresql.md)
**List PostgreSQL extensions**
**Operation ID:** `listPGExtensions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | Organization name |
| `clusterName` | path | string | Yes | name of the cluster |
| `status` | query | string | No | extension status, if set to `installed`, only installed extensions will be returned. If not specified, all available extensions will be returned. |
| `database` | query | string | No | database name. This parameter is only used when status is installed; if not specified, all databases installed extensions will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[PgExtensionList](../schemas/Pg/PgExtensionList.md)

