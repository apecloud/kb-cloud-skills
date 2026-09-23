# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys

**Resource:** [rdbms](../resources/rdbms.md)
**List MinIO access keys**
**Operation ID:** `listServiceAccounts`

list MinIO service account access keys

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `userName` | query | string | No | MinIO user that owns the service accounts |

## Responses

| Status | Description |
|--------|-------------|
| 200 | list MinIO access keys success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsServiceAccountList](../schemas/Dms/DmsServiceAccountList.md)

