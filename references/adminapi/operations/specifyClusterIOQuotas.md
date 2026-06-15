# POST /admin/v1/organizations/{orgName}/clusters/{clusterName}/volumes/io-quotas

**Resource:** [opsrequest](../resources/opsrequest.md)
**Specify IOPS and BPS of cluster volumes**
**Operation ID:** `specifyClusterIOQuotas`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [opsIoQuotas](../schemas/opsIoQuotas/opsIoQuotas.md)

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

