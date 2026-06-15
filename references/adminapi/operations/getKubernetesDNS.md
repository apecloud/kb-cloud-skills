# POST /admin/v1/kubernetes/dns

**Resource:** [environment](../resources/environment.md)
**Get Kubernetes DNS**
**Operation ID:** `getKubernetesDNS`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [kubeconfig](../schemas/kubeconfig/kubeconfig.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dns](../schemas/dns/dns.md)

