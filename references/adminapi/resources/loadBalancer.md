# loadBalancer

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/v1/environments/{environmentName}/loadbalancer` | Get the load balancer info in the environment | [View](../operations/getLoadBalancer.md) |
| POST | `/admin/v1/environments/{environmentName}/loadbalancer/check` | Check if the load balancer is available | [View](../operations/checkLoadBalancer.md) |
| GET | `/admin/v1/environments/{environmentName}/loadbalancer/config` | Get the effective load balancer configuration of an environment | [View](../operations/getLoadBalancerConfig.md) |
| PUT | `/admin/v1/environments/{environmentName}/loadbalancer/config` | Save and immediately activate the load balancer configuration of an environment | [View](../operations/updateLoadBalancerConfig.md) |
| DELETE | `/admin/v1/environments/{environmentName}/loadbalancer/config` | Reset the environment load balancer configuration to the current provider defaults | [View](../operations/resetLoadBalancerConfig.md) |
