---
title: 'aria-busy'
attributions:
  - 'Microsoft Developer Network: [[Windows Internet Explorer API reference](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx) Article]'
compatibility:
  feature: aria-busy
  topic: aria
notes:
  - 'Needs summary, example, spec reference, standardization status'
readiness: 'Not Ready'
tags:
  - Markup_Attributes
  - ARIA
  - Needs_Summary
  - Needs_Examples
uri: aria/attributes/aria-busy

---
<table class="wikitable">
<tr>
<th>
Applies to

</th>
<td>
</td>
</tr>
</table>
## Notes

### Remarks

<table class="wikitable">
<tr>
<th>
Used in Roles

</th>
<td>
<dl>

<dt>
No role required.

</dt>
</dl>
</td>
</tr>
</table>
  This property applies to live regions in the user interface. If authors know that multiple parts of the same live region need to be loaded, they can set **aria-busy** to **true** when the first part is loaded, and then set it to **false** when the last part is loaded. **Note**  For cross-browser compatibility, always use the WAI-ARIA attribute syntax to access and modify ARIA properties, for example `object.setAttribute("aria-valuenow", newValue)`.

### Syntax

### Standards information

-   [Accessible Rich Internet Applications (WAI-ARIA) 1.0](http://go.microsoft.com/fwlink/p/?linkid=203793), Section 6.6

## See also

### Related pages

-   Accessible Rich Internet Applications (ARIA)[Accessible Rich Internet Applications (ARIA)](/aria)
-   W3C ARIA-Busy[W3C ARIA-Busy](http://go.microsoft.com/fwlink/p/?linkid=203793)
