# POST /admin/v1/organizations/{orgName}/resourceQuota

**Resource:** [organizationResourceQuota](../resources/organizationResourceQuota.md)
**Update the resource quota of an organization**
**Operation ID:** `resourceQuota`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [orgResourceQuota](../schemas/orgResourceQuota/orgResourceQuota.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | OK |
| 401 | (reference) |
| 403 | (reference) |

