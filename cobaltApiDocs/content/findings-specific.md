---
weight: 14
title: Get Specific Findings
---

## Get Specific Findings

```shell
curl -X GET "https://api.cobalt.io/findings?pentest=pt_9Ig" 
  -H "accept: application/vnd.cobalt.v1+json" 
  -H "Authorization: Bearer your-personal-api-token-here" 
  -H "X-Org-Token: your-org-token-here"

```

You can filter for findings scoped to a pentest or to an asset.

### HTTP Requests

`GET https://api.cobalt.io/findings?pentest=pt_9Ig`

`GET https://api.cobalt.io/findings?asset=as_cwrsqsL`

### URL Parameters

Parameter | Default | Description
--------- | ------- | -----------
pentest | n/a | If specified, returns findings scoped to this pentest id, e.g. https://api.cobalt.io/findings?pentest=pt_9Ig
asset | n/a | If specified, returns findings scoped to this asset id, e.g. https://api.cobalt.io/findings?asset=as_cwrsqsL

