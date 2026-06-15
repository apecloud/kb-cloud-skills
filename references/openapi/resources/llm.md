# llm

LLM APIs

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v1/organizations/{orgName}/llm` | List available LLM for org | [View](../operations/ListLLMForOrg.md) |
| POST | `/api/v1/organizations/{orgName}/llm` | add LLM for org | [View](../operations/addLLMForOrg.md) |
| GET | `/api/v1/organizations/{orgName}/llm/{id}` | Get LLM by ID in org | [View](../operations/getLLMByIDInOrg.md) |
| DELETE | `/api/v1/organizations/{orgName}/llm/{id}` | Delete LLM | [View](../operations/deleteLLM.md) |
| PATCH | `/api/v1/organizations/{orgName}/llm/{id}` | Update LLM | [View](../operations/updateLLM.md) |
| POST | `/api/v1/organizations/{orgName}/llm/check` | check apikey available for org | [View](../operations/checkAPIKeyForOrg.md) |
| GET | `/api/v1/organizations/{orgName}/llm/models` | List available model in org | [View](../operations/listAvailableModelInOrg.md) |
