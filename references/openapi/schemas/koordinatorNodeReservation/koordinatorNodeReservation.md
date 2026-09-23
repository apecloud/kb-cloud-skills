# koordinatorNodeReservation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resourceClass` | [koordinatorReservationResourceClass](koordinatorReservationResourceClass.md) | Yes |  |
| `reservationName` | string | No |  |
| `resources` | [koordinatorReservationResources](koordinatorReservationResources.md) | Yes |  |
| `ttl` | string | No | Kubernetes duration string. Koordinator defaults omitted ttl to 24h. |
| `allocateOnce` | boolean | No |  |
| `preAllocation` | boolean | No |  |
| `allocatePolicy` | [koordinatorReservationAllocatePolicy](koordinatorReservationAllocatePolicy.md) | No |  |
| `status` | [koordinatorReservationStatus](koordinatorReservationStatus.md) | No |  |

