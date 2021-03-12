---
weight: 17
title: Refresh Token
---

## Refresh Token

```shell
curl -X PUT "https://api.cobalt.io/tokens/token-id-here/refresh" 
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

You can request a new token with a PUT request to the token refresh endpoint, referencing the token id fetched from the GET token list endpoint.


### HTTP Request

`PUT https://api.cobalt.io/tokens/token-id-here/refresh`

