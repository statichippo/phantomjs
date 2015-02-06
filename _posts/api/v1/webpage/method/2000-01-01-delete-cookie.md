---
layout: post
title:  deleteCookie
categories: api_v1 webpage webpage-method
permalink: api/v1/webpage/method/delete-cookie.html
---

`deleteCookie(cookieName)` {boolean}

**Introduced:** PhantomJS 1.7

Delete any Cookies visible to the current URL with a 'name' property matching `cookieName`. Returns `true` if successfully deleted, otherwise `false`.

## Examples

```javascript
var webPage = require('webpage');
var page = webPage.create();

page.deleteCookie('Added-Cookie-Name');
```







