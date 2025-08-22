# Quick Start Guide

> **Audience:** Developers new to the API  
> **Goal:** Make a first successful request in <10 minutes

## Prerequisites
- A valid API key or token (see **Authentication**)
- A tool to send HTTP requests:
  - Postman (recommended)
  - VS Code + REST Client extension
  - `curl`

## Base URL
```
https://api.example.com/v1
```

## Authentication
Use a Bearer token in the `Authorization` header:

```
Authorization: Bearer YOUR_TOKEN
```

## Your First Call: List Items
**GET** `/items?limit=5`

### Example Response
```json
{
  "data": [
    {"id": "itm_123", "name": "Widget", "price": 19.99}
  ]
}
```

---
