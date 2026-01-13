
---

## 📄 `docs/endpoints/sample-endpoint.md`
```markdown
# GET /v1/tasks/{taskId}

## Description
Retrieves details for a specific task by its unique identifier.

## Authentication
Requires a valid Bearer token.

## Request

### Headers
| Name          | Required | Description              |
|---------------|----------|--------------------------|
| Authorization | Yes      | Bearer authentication token |

### Path Parameters
| Name   | Required | Description        |
|--------|----------|--------------------|
| taskId | Yes      | Unique task ID     |

## Example Request
```http
GET /v1/tasks/123
Authorization: Bearer abc123token
