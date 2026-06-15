# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/updateLicense

**Resource:** [opsrequest](../resources/opsrequest.md)
**Update the cluster license**
**Operation ID:** `updateClusterLicense`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsLicense](../schemas/opsLicense/opsLicense.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

