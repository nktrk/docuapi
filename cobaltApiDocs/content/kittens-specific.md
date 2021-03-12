---
weight: 14
title: Get Specific Findings
---

## Get Specific Findings

```shell
curl -X GET "https://api.cobalt.io/findings?" 
  -H "accept: application/vnd.cobalt.v1+json" 
  -H "Authorization: Bearer your-personal-api-token-here" 
  -H "X-Org-Token: your-org-token-here"

```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

