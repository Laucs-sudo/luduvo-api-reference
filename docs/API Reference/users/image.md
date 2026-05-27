---
title: Avatar
---
### <span class="badge badge-get">GET</span> <span class="endpoint">/users/:id/avatar/headshot</span>

Get user avatar headshot

#### Parameters

| Parameter | Description | Type | Required |
|-----------|-------------|------|----------|
| id | Luduvo User ID | Path | Yes |
| size | Target image resolution | Query | No |

#### Authentication

| Type | Required |
|------|----------|
| None | No |

#### Example Response

```
HTTP/1.1 302 Found
Location: https://luduvo.com
Content-Length: 0
```

---
