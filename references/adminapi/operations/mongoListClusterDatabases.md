# GET /admin/v1/data/mongodb/organizations/{orgName}/clusters/{clusterName}/databases

**Resource:** [mongodb](../resources/mongodb.md)
**List MongoDB cluster databases**
**Operation ID:** `mongoListClusterDatabases`

Lists existing database names using the cluster management connection. Does not require a personal Workbench datasource.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes |  |
| `clusterName` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Database names, sorted; an empty result is an empty array. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema** (inline):

Array

