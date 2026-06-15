# PATCH /admin/v1/monitorDataSinks/{monitorDataSinkID}

**Resource:** [monitorDataSink](../resources/monitorDataSink.md)
**Update the specified monitor data sink**
**Operation ID:** `patchMonitorDataSink`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `monitorDataSinkID` | path | string | Yes | monitor data sink id |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [monitorDataSinkUpdate](../schemas/monitorDataSinkUpdate/monitorDataSinkUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[monitorDataSink](../schemas/monitorDataSink/monitorDataSink.md)

