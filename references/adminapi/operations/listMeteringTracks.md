# GET /admin/v1/metering/tracks

**Resource:** [metering](../resources/metering.md)
**List metering tracks**
**Operation ID:** `listMeteringTracks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `clusterID` | query | string | No | The ID of the cluster |
| `orgName` | query | string | No | Name of organization |
| `projectName` | query | string | No | name of the project |
| `environmentName` | query | string | No | The name of the environment |
| `pageNumber` | query | integer (int64) | No | the pageNumber of the query |
| `pageSize` | query | integer (int64) | No | the pageSize of the query |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List metering tracks |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[MeteringTrackList](../schemas/Metering/MeteringTrackList.md)

