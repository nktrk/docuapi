---
weight: 16
title: Refresh Token
---

## Refresh Specific Findings

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

`PUT https://api.cobalt.io/tokens/:token-id-here/refresh`

### URL Parameters

Parameter | Default | Description
--------- | ------- | -----------
pentest | n/a | If specified, returns findings scoped to this pentest id, e.g. https://api.cobalt.io/findings?pentest=pt_9Ig
asset | n/a | If specified, returns findings scoped to this asset id, e.g. https://api.cobalt.io/findings?asset=as_cwrsqsL

