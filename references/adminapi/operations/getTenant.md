# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/tenant/{tenantId}

**Resource:** [oceanbase](../resources/oceanbase.md)
**get tenants detail information of the oceanbase cluster**
**Operation ID:** `getTenant`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |
| `tenantId` | path | string | Yes | id of the tenant |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[Tenant](../schemas/Tenant/Tenant.md)

