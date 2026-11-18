# vipPool

VIP Pool APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/environments/{environmentName}/loadbalancer/vipPool` | List environment VIP Pools | [View](../operations/listVIPPool.md) |
| POST | `/admin/v1/environments/{environmentName}/loadbalancer/vipPool` | Create environment VIP Pool | [View](../operations/createVIPPool.md) |
| POST | `/admin/v1/environments/{environmentName}/loadbalancer/vipPool/checkPorts` | Check whether ports are already used on a VIP | [View](../operations/checkVIPPorts.md) |
| PUT | `/admin/v1/environments/{environmentName}/loadbalancer/vipPool/{poolID}` | Update environment VIP Pool | [View](../operations/updateVIPPool.md) |
| DELETE | `/admin/v1/environments/{environmentName}/loadbalancer/vipPool/{poolID}` | Delete environment VIP Pool | [View](../operations/deleteVIPPool.md) |
