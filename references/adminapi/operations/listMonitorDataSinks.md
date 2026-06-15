# GET /admin/v1/monitorDataSinks/environments/{environmentName}

**Resource:** [monitorDataSink](../resources/monitorDataSink.md)
**Get monitor data sink list**
**Operation ID:** `listMonitorDataSinks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | kubernetes environment name which monitor data sink deployed in. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[monitorDataSinkList](../schemas/monitorDataSinkList/monitorDataSinkList.md)

