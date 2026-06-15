# GET /admin/v1/organizations/{orgName}/clusters/{clusterName}/instances/{instanceName}/log

**Resource:** [cluster](../resources/cluster.md)
**Tail cluster instance container log**
**Operation ID:** `getInstanceContainerLog`

read log of the specified cluster instance

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |
| `clusterName` | path | string | Yes | name of the KubeBlocks cluster |
| `instanceName` | path | string | Yes | name of the instance |
| `container` | query | string | No | specify container name to get specific container log, if not specified, will return the log of the default container |
| `sinceSeconds` | query | integer | No | A relative time in seconds before the current time from which to show logs. If this value precedes the time a pod was started, only logs since the pod start will be returned. If this value is in the future, no logs will be returned. Only one of sinceSeconds or sinceTime may be specified. |
| `tailLines` | query | integer | No | If set, the number of lines from the end of the logs to show. If not specified, logs are shown from the creation of the container or sinceSeconds or sinceTime |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[instanceLog](../schemas/instanceLog/instanceLog.md)

