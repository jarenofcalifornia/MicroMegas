# MicroMegas Info
Micromegas is a granular sampler and looper, made for live performance. <br>
It can record and overdub live-audio in any speed or direction. It can overdub over any part of an original recording. <br>
It can play back these samples as a powerful looper, and/or as a polyphonic granular synthesizer. <br>
The looper has granular parameters, and the granular synthesizer can act as a time-pitch independent looper. Sync 'em. <br>

Micromegas is a Max for Live audio device. It works in Ableton Live. <br>
Place MicroMegas in an audio track, and place the included "Micromegas MIDI Sender" in a MIDI track. <br>

I've made two versions of MicroMegas. <br>
----"MicroMegas with SoftStep" contains code that allows the Softstep footpedal to control the parameters in powerful ways.
----"MicroMegas" is without SoftStep control, and thus has a couple extra GUI elements.


Bugs:

----Sometimes the karma~ object does not initialize, and one must open the patch and reinitialize the object. <br>
----Sometimes a MIDI note does not properly release. Workaround: trigger a number of voices greater than the max setting in the "Voice" param.

Micromegas is based on by Robert Henke's Granualtor II synthesizer, and Robert Constanzo and Raja's karma~ live-sampler. Both were released for free. Thanks guys.
