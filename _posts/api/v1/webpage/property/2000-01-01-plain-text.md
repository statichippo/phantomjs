---
layout: post
title:  plainText
categories: api_v1 webpage webpage-property
permalink: api/v1/webpage/property/plain-text.html
---

`plainText` {string}

Read-only. This property stores the content of the web page (main frame) as plain text &mdash; no element tags!

See also: `page.content` which returns the content with element tags.

## Examples

```javascript
var webPage = require('webpage');
var page = webPage.create();

page.open('http://phantomjs.org', function (status) {
  console.log('Stripped down page text:\n' + page.plainText);
  phantom.exit();
});
```







