# PATCH /admin/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys/{accessKey}

**Resource:** [rdbms](../resources/rdbms.md)
**Update MinIO access key**
**Operation ID:** `updateServiceAccount`

update a MinIO service account access key

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |
| `accessKey` | path | string | Yes | MinIO access key |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsServiceAccountUpdateRequest](../schemas/Dms/DmsServiceAccountUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | update MinIO access key success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsServiceAccount](../schemas/Dms/DmsServiceAccount.md)

