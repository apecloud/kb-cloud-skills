# POST /admin/v1/data/kafka/organizations/{orgName}/clusters/{clusterName}/topics

**Resource:** [kafka](../resources/kafka.md)
**Create new topic**
**Operation ID:** `createKafkaTopic`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `orgName` | path | string | Yes | The name of organization |
| `clusterName` | path | string | Yes | The name of cluster |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateTopicRequest](../schemas/Create/CreateTopicRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[Topic](../schemas/Topic/Topic.md)

