# POST /admin/v1/monitorDataSinks

**Resource:** [monitorDataSink](../resources/monitorDataSink.md)
**Create monitor data sink**
**Operation ID:** `createMonitorDataSink`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [monitorDataSinkCreate](../schemas/monitorDataSinkCreate/monitorDataSinkCreate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[monitorDataSink](../schemas/monitorDataSink/monitorDataSink.md)

