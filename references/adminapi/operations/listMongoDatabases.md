# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/datasource/{id}/mongodb/databases

**Resource:** [dms](../resources/dms.md)
**list MongoDB databases**
**Operation ID:** `listMongoDatabases`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `id` | path | string | Yes | id of the datasource |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |

**Success Response Schema** (inline):

Array

