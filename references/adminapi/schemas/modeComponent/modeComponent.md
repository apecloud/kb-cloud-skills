# modeComponent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `component` | string | Yes |  |
| `hideEnpoints` | boolean | Yes |  |
| `hideOnCreate` | boolean | Yes |  |
| `instanceTemplate` | object | No | Template fields and operations shared by the frontend and backend.
Requested components require creation template targets when instanceTemplate is declared.
Declaring hscale or storageExpansion in ops requires explicit targets
for every name. The hscale requirement applies to replica scaling only.
 |
| `serviceRef` | string | No | the name of the serviceRef defined in mode's serviceRefs.
If set, it means a serviceRef can be used to replace this component.
 |
| `readonlyEndpoint` | [modeReadonlyEndpoint](modeReadonlyEndpoint.md) | No |  |

## Nested Fields

### `instanceTemplate`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `names` | string[] | Yes | Instance template names the frontend should render.
Create checks names against the chart. Replica hscale and volume expansion
targets must include every name in this list.
 |
| `ops` | instanceTemplateOp[] | Yes | Template operations: hscale, storageExpansion, and reserved vscale.
Template hscale replicas must sum to the component target.
Volume expansion targets must match component volume names and capacities.
 |
| `attributes` | instanceTemplateAttribute[] | No | Heterogeneous attributes the frontend should render on each
instance template at create. Omitted or empty means only name
and replicas. Create overlays the request onto the chart and
does not re-check this list.
 |
| `env` | instanceTemplateEnv[] | No | Env vars the frontend may render when attributes includes env.
Create does not re-check this list.
 |

