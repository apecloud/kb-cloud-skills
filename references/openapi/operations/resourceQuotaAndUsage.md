# GET /api/v1/organizations/{orgName}/resourceQuota

**Resource:** [organizationResourceQuota](../resources/organizationResourceQuota.md)
**Get the resource quota and usage of an organization**
**Operation ID:** `resourceQuotaAndUsage`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of the organization |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

[orgResourceQuotaAndUsage](../schemas/orgResourceQuotaAndUsage/orgResourceQuotaAndUsage.md)

