# GET /api/v1/organizations/{orgName}/environments/{environmentName}/koordinatorReservations/summary

**Resource:** [environment](../resources/environment.md)
**List Koordinator Reservations**
**Operation ID:** `listKoordinatorReservations`

Get Koordinator Reservation summary for the cluster creation page.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | name of the Organization |
| `environmentName` | path | string | Yes | name of the Environment |

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

