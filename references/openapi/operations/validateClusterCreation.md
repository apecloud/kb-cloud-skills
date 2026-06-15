# POST /api/v1/organizations/{orgName}/clusters/validate

**Resource:** [cluster](../resources/cluster.md)
**Validate cluster creation**
**Operation ID:** `validateClusterCreation`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [clusterCreate](../schemas/clusterCreate/clusterCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Return when cluster creation is validated successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

