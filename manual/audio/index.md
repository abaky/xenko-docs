# Audio

The Xenko engine includes a fully featured audio sub system, that allows to play audio samples from buffers or directly stream compressed streams from disk. It also allows full 3D spatialization of sound and low latency playback.
From the Game Studio it is possible to import any kind of audio file which internally gets compressed with the best current open source technology of [Opus/Celt](https://en.wikipedia.org/wiki/CELT) codec to reduce and compress the data yet preserving high quality.

The most common scenario is to import sounds from the Game Studio and than reference them in Scripts or consume them directly from an `AudioEmitterComponent`, in this case since it's meant to be used for 3D spatialization you also will need a `AudioListenerComponent`.

### Topics:
[Import Audio files]()
[Playing sounds from scripts]()




