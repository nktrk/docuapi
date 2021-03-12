---
weight: 16
title: Tokens
---

# Tokens

## Get All Tokens

```shell
curl -X GET "https://api.cobalt.io/tokens" 
  -H "accept: application/vnd.cobalt.v1+json" 
  -H "Authorization: Bearer your-personal-api-token-here" 

```

> The above command returns JSON structured like this:

```json
{
  "data": [
    {
      "resource": {
        "id": "WIP"
      }
    }
 ]
}

```

This endpoint retrieves a list of all tokens that belong to you.

### HTTP Request

`GET https://api.cobalt.io/tokens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
limit | 100 | If set, you can adjust the limit returned, e.g. https://api.cobalt.io/tokens?limit=1000
