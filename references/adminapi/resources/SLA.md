# SLA

SLA APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/sla` | Calculate SLA for a environment | [View](../operations/CalculateSLA.md) |
| GET | `/admin/v1/sla/rank` | List SLA rank for a environment | [View](../operations/ListSLARank.md) |
| GET | `/admin/v1/sla/daily` | Calculate daily SLA for a environment or a cluster since a specific date | [View](../operations/CalculateDailySLA.md) |
| GET | `/admin/v1/sla/outages` | List outage record for environments | [View](../operations/ListEnvironmentOutageRecord.md) |
| GET | `/admin/v1/sla/settings` | Get SLA settings | [View](../operations/GetSLASettingsInEnv.md) |
| PATCH | `/admin/v1/sla/settings` | Update SLA settings | [View](../operations/UpdateSLASettingsInEnv.md) |
| GET | `/admin/v1/sla/engines` | Get SLA supported engines | [View](../operations/GetSLASupportEngines.md) |
| GET | `/admin/v1/sla/uncompliant` | List uncompliant clusters | [View](../operations/ListUncompliantClusters.md) |
