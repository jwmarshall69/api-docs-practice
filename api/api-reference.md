# API Reference

## List Items

**GET** `/v1/items`

### Query Parameters

| Name | Type | Required | Description |
|------|------|----------|-------------|
| limit | integer | No | Number of items to return |

### Response

```json
{
  "data": [
    {"id": "itm_123", "name": "Widget", "price": 19.99}
  ]
}
```

---
