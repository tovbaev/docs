---
title: 'setValueCurveAtTime'
readiness: 'Ready to Use'
relationships:
  method_of:
    predicate: 'Method of '
    value: apis/webaudio/AudioParam
    href: /apis/webaudio/AudioParam
  return_type:
    predicate: 'Returns an object of type  '
    value: ''
    href: /apis/webaudio/AudioParam
standardization_status: 'W3C Editor''s Draft'
summary: 'Sets an array of arbitrary parameter values starting at the given time for the given duration. The number of values will be scaled to fit into the desired duration.'
tags:
  - API_Object_Methods
  - API
  - WebAudio
uri: apis/webaudio/AudioParam/setValueCurveAtTime

---
## Summary

Sets an array of arbitrary parameter values starting at the given time for the given duration. The number of values will be scaled to fit into the desired duration.

Method of [apis/webaudio/AudioParam](/apis/webaudio/AudioParam)[apis/webaudio/AudioParam](/apis/webaudio/AudioParam)

## Syntax

``` js
var  = AudioParam.setValueCurveAtTime(values, startTime, duration);
```

## Parameters

### values

 Data-type
:   String

 A **Float32Array** representing a parameter value curve. These values will apply starting at the given time and lasting for the given duration.

### startTime

 Data-type
:   Number

 The time in the same time coordinate system as [**AudioContext.currentTime**](/apis/webaudio/AudioContext/currentTime).

### duration

 Data-type
:   Number

 The amount of time in seconds (after the time parameter) where values will be calculated according to the values parameter.

## Return Value

Returns an object of type

## Examples

``` js
var gainNode = audioCtx.createGain();
gainNode.gain.setValueCurveAtTime(waveArray, audioCtx.currentTime, 2); //'gain' is the AudioParam
```

## Related specifications

[W3C Web Audio API](http://webaudio.github.io/web-audio-api/)
:   W3C Editor's Draft
