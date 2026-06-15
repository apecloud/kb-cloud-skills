# POST /api/v1/organizations/{orgName}/clusters/{clusterName}/volume-expand

**Resource:** [opsrequest](../resources/opsrequest.md)
**Expand cluster volume size**
**Operation ID:** `clusterVolumeExpand`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsVolumeExpand](../schemas/opsVolumeExpand/opsVolumeExpand.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

