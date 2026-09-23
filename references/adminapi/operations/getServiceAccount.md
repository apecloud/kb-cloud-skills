# GET /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys/{accessKey}

**Resource:** [rdbms](../resources/rdbms.md)
**Get MinIO access key**
**Operation ID:** `getServiceAccount`

get a MinIO service account access key

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accessKey` | path | string | Yes | MinIO access key |

## Responses

| Status | Description |
|--------|-------------|
| 200 | get MinIO access key success |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsServiceAccount](../schemas/Dms/DmsServiceAccount.md)

