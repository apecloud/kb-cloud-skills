# GET /admin/v1/environments/{environmentName}/koordinatorReservations/summary

**Resource:** [environment](../resources/environment.md)
**Get Koordinator Reservation summary**
**Operation ID:** `getKoordinatorReservationSummary`

Get Koordinator Reservation summary for the cluster creation page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `environmentName` | path | string | Yes | name of the environment |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Koordinator Reservation summary. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[koordinatorReservationSummary](../schemas/koordinatorReservationSummary/koordinatorReservationSummary.md)

