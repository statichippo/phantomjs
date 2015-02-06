---
layout: post
title:  Callback Triggers
categories: api_v1 webpage webpage-handler
permalink: api/v1/webpage/handler/callback-triggers.html
---

These functions call callbacks, used for tests...

* `closing(page)`
* `initialized()`
* `javaScriptAlertSent(message)`
* `javaScriptConsoleMessageSent(message)`
* `loadFinished(status)`
* `loadStarted()`
* `navigationRequested(url, navigationType, navigationLocked, isMainFrame)`
* `rawPageCreated(page)`
* `resourceError(resource)`
* `resourceReceived(request)`
* `resourceRequested(resource)`
* `urlChanged(url)`