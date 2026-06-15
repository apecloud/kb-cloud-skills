# GET /api/v1/organizations/{orgName}/clusters/{clusterName}/tenants

**Resource:** [oceanbase](../resources/oceanbase.md)
**list all tenants for the oceanbase cluster**
**Operation ID:** `listTenants`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the cluster |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[TenantList](../schemas/Tenant/TenantList.md)

