# engineOptionHistory

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `modifierId` | string | Yes |  |
| `modifierEmail` | string | No |  |
| `option` | object | Yes | Engine option document stored when this history row was written.
This is a point-in-time snapshot, not the current engineOption
create/update contract. Nested fields such as endpoints.protocol
may be absent on older rows.
 |
| `createdAt` | string (date-time) | Yes |  |

