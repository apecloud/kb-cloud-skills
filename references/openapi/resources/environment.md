# environment

Environment APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/environments` | List environments | [View](../operations/listEnvironment.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}` | Get environment | [View](../operations/getEnvironment.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}/availableZones` | List the availability zones where the environment's nodes are located | [View](../operations/listEnvNodeZone.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}/network/ipPools` | Discover Pod IP pools and explicit selection policy in an environment | [View](../operations/listEnvironmentIPPools.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}/koordinatorReservations/summary` | List Koordinator Reservations | [View](../operations/listKoordinatorReservations.md) |
| GET | `/api/v1/environments/{environmentName}/nodeGroups` | List environment node group | [View](../operations/listNodeGroup.md) |
| GET | `/api/v1/environments/{environmentName}/modules` | Get environment module information in an environment | [View](../operations/getEnvironmentModuleInfo.md) |
