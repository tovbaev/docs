---
title: 'byteOffset'
attributions:
  - 'Microsoft Developer Network: [Article](http://msdn.microsoft.com/en-us/library/ie/br212912(v=vs.94).aspx)'
compatibility:
  feature: byteOffset
  topic: javascript
readiness: 'Ready to Use'
summary: 'Read-only. The offset of this view from the start of its ArrayBuffer, in bytes, as fixed at construction time.'
tags:
  - JS_Basic
uri: javascript/DataView/byteOffset

---
## Summary

Read-only. The offset of this view from the start of its ArrayBuffer, in bytes, as fixed at construction time.

## Syntax

    var arrayOffset = dataView.byteOffset;

## Examples

The following example shows how to get the length of a DataView.

``` js
var req = new XMLHttpRequest();
     req.open('GET', "http://www.example.com");
     req.responseType = "arraybuffer";
     req.send();

     req.onreadystatechange = function () {
         if (req.readyState === 4) {
             var buffer = req.response;
             var dataView = new DataView(buffer);
             alert(dataView.byteOffset)
         }
     }
```

