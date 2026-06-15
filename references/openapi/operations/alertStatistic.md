# GET /api/v1/alerts/statistic

**Resource:** [alert](../resources/alert.md)
**alert statistic**
**Operation ID:** `alertStatistic`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | query | string | No | name of the Org |

## Responses

| Status | Description |
|--------|-------------|
| 200 | A successful response. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[alertStatistic](../schemas/alertStatistic/alertStatistic.md)

