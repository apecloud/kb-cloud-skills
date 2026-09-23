# POST /api/v1/data/{engineName}/organizations/{orgName}/clusters/{clusterName}/access-keys

**Resource:** [rdbms](../resources/rdbms.md)
**Create MinIO access key**
**Operation ID:** `createServiceAccount`

create a MinIO service account access key

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `engineName` | path | string | Yes | name of the engine |
| `orgName` | path | string | Yes | name of the organization |
| `clusterName` | path | string | Yes | name of the cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DmsServiceAccountCreateRequest](../schemas/Dms/DmsServiceAccountCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | create MinIO access key success |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[DmsServiceAccount](../schemas/Dms/DmsServiceAccount.md)

