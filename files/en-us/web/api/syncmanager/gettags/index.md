---
title: SyncManager.getTags()
slug: Web/API/SyncManager/getTags
tags:
  - API
  - Experimental
  - Method
  - Reference
  - ServiceWorker
  - SyncManager
  - getTags
browser-compat: api.SyncManager.getTags
---
{{APIRef("Service Workers API")}}{{Non-standard_header}}

The **`SyncManager.getTags`** method of the
{{domxref("SyncManager")}} interface returns a list of developer-defined identifiers for
`SyncManager` registrations.

## Syntax

```js
SyncManager.getTags().then(function(tags[]) { /* ... */ })
```

### Returns

A {{jsxref("Promise")}} that resolves to an array of strings
containing developer-defined identifiers for `SyncManager` registrations.

### Parameters

None.

## Browser compatibility

{{Compat}}
