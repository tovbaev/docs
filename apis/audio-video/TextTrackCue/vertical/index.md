---
title: 'vertical'
attributions:
  - 'Microsoft Developer Network: [Windows Internet Explorer API reference Article](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx)'
readiness: 'Ready to Use'
relationships:
  applies_to:
    predicate: 'Property of '
    value: apis/audio-video/TextTrackCue
    href: /apis/audio-video/TextTrackCue
  return:
    predicate: 'Returns an object of type '
    value: String
    href: /apis/audio-video/TextTrackCue
standardization_status: 'W3C Editor''s Draft'
summary: 'A string representing the text track cue writing direction, as follows. If it is horizontal: The empty string. If it is vertical growing left: The string &quot;rl&quot;. If it is vertical growing right: The string &quot;lr&quot;.'
tags:
  - API_Object_Properties
  - API
  - Audio
  - Video
uri: apis/audio-video/TextTrackCue/vertical

---
## Summary

A string representing the text track cue writing direction, as follows. If it is horizontal: The empty string. If it is vertical growing left: The string &quot;rl&quot;. If it is vertical growing right: The string &quot;lr&quot;.

Property of [apis/audio-video/TextTrackCue](/apis/audio-video/TextTrackCue)[apis/audio-video/TextTrackCue](/apis/audio-video/TextTrackCue)

## Syntax

``` js
var result = TextTrackCue.vertical;
TextTrackCue.vertical = value;
```

## Return Value

Returns an object of type StringString

## Examples

``` js
//. . .
var myTrack = document.getElementById("entrack").track; // get text track from track element
var myCues = myTrack.cues;   // get list of cues
for (var i = 0; i < myCues.length; i++) {
// set each cue's vertical flag to vertical-growing-right
myCues[i].vertical = "lr";
}
//. . .
```

## Usage

     "Horizontal" writing direction means a text line extends horizontally and is positioned vertically, with consecutive lines displayed below each other. "Vertical growing left" means a text line extends vertically and is positioned horizontally, with consecutive lines displayed to the left of each other. "Vertical growing right" means a text line extends vertically and is positioned horizontally, with consecutive lines displayed to the right of each other.

## Related specifications

[W3C HTML5 Specification](http://dev.w3.org/html5/spec/single-page.html)
:   W3C Editor's Draft
