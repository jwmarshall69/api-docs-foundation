
---

## 📄 `docs/errors.md`
```markdown
# Error Handling

This API returns standard HTTP status codes and a consistent error object.

## Error Object
| Field      | Type   | Description                         |
|------------|--------|-------------------------------------|
| code       | string | Application-specific error code     |
| message    | string | Human-readable error description    |
| requestId  | string | Unique ID for troubleshooting       |

## Example Error Response
```json
{
  "code": "TASK_NOT_FOUND",
  "message": "The requested task does not exist.",
  "requestId": "req-789456"
}
