---
weight: 10
title: API Reference
---

# Introduction

Welcome to the Cobalt.io API. You can use our API to access information on orgs, assets, pentests, findings and events from our database.

We have language bindings in Shell, Ruby, and Python! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

<!---
**This example API documentation page was created with [DocuAPI](https://github.com/bep/docuapi/), a multilingual documentation theme for the static site generator [Hugo](http://gohugo.io/).** 
-->

# Authentication

> To authorize, use this code:

```shell
# With shell, you can just pass the correct header with each request
curl "https://api.cobalt.io"
  -H "Authorization: Bearer your-personal-API-token-here"
```

> Make sure to replace `your-personal-API-token-here` with your API token.

Cobalt uses API tokens to allow access to the API. You can create a new Cobalt API token from within your [Cobalt Profile](https://app.cobalt.io/settings/api-token).

Cobalt expects for the API token to be included in all API requests to the server in a header that looks like the following:

`Authorization: Bearer your-personal-API-token-here`

<aside class="notice">
You must replace <code>your-personal-API-token-here</code> with your personal API token. Make sure _not_ to remove the word Bearer.
</aside>
