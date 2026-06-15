# DELETE /api/v1/organizations/{orgName}/benchmark

**Resource:** [benchmark](../resources/benchmark.md)
**Delete benchmark tasks**
**Operation ID:** `deleteBenchmark`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Org |

## Request Body

ids of the benchmark

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [deleteBenchOption](../schemas/deleteBenchOption/deleteBenchOption.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned when project is deleted successfully. |
| 403 | (reference) |
| 404 | (reference) |

