# POST /admin/v1/environments/preflight

**Resource:** [environment](../resources/environment.md)
**Preflight check before create Environment**
**Operation ID:** `preflightEnvironment`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [kubeconfig](../schemas/kubeconfig/kubeconfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[preflightList](../schemas/preflightList/preflightList.md)

