# environment

Environment APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/environments` | List environments | [View](../operations/listEnvironment.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}` | Get environment | [View](../operations/getEnvironment.md) |
| GET | `/api/v1/organizations/{orgName}/environments/{environmentName}/availableZones` | List the availability zones where the environment's nodes are located | [View](../operations/listEnvNodeZone.md) |
| GET | `/api/v1/environments/{environmentName}/nodeGroups` | List environment node group | [View](../operations/listNodeGroup.md) |
| GET | `/api/v1/environments/{environmentName}/modules` | Get environment module information in an environment | [View](../operations/getEnvironmentModuleInfo.md) |
