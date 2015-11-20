# MicroMegas Info
Micromegas is a granular sampler and looper, made for live performance.
It can record and overdub live-audio in any speed or direction. It can overdub over any part of an original recording.
It can play back these samples as a powerful looper, and/or as a polyphonic granular synthesizer. 
These two modes are interrelated, and can be synced together.
The looper has quasi-granular parameters, and the granular synthesizer can act as a time-pitch independent looper.

Micromegas is a Max for Live audio device, and works in Ableton. It has two sister devices that route it MIDI.
Micromegas is programmed to work with the SoftStep footpedal. 
Certain functions (such as quantized Speed and Grainsize settings) can only be accessed through the SoftStep interface.
Place Micromegas in an audio track, and the two sister devices in MIDI tracks, make sure the MIDI bus #s (found on GUI) are corrolated.
For the "Softstep MIDI Sender" to work, make sure your SoftStep Advanced Editor is open, and your Live MIDI track is set to send/receive from SSCOM (Port 1).

Known bugs:
Sometimes the karma~ object does not initialize, and one must open the patch and reinitialize the object.
Sometimes a MIDI note does not properly release. Workaround: trigger a number of voices greater than the max setting in the "Voice" param.

Micromegas is based on and made possible by Robert Henke's Granualtor II synthesizer, and Robert Constazo and Raja's karma~ live-sampler.
