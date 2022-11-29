---
title: "Vulpus Labs"
date: 2022-10-19T23:54:55+01:00
draft: false
author: Dominic Fox
---
Vulpus Labs make music software.

Initial releases will be [Voltage Modular](https://cherryaudio.com/products/voltage-modular) plugins, beginning with the forthcoming...

# Cross Fade Grid

{{< figure src="/media/crossfadegrid.png" title="Cross Fade Grid" >}}

The basic premise is that you have four inputs and one outputs, and an eight-step sequencer grid that you can use to select which input is sent to the output at each step. When switching between inputs, a smooth (cosine curve) crossfade is applied, of controllable length. The stepping of the sequencer is driven by an external clock (something that fires BPM-controlled triggers, or just an LFO).

Uses:
* _Trance Gapper_ - switch between a sound source and an unconnected input to get a rhythmic "gapping" effect, in a pattern of your choosing
* _Rhythmic modulation_ - route the same input source into multiple effects signal chains, and use the grid to switch rhythmically between them, e.g. alternating between a clean and a distorted or filtered signal.
* _Source interleaving_ - interleave multiple input sources, e.g. a guitar and a sequenced synth pattern, or oscillator tones tuned to different pitches for a rudimentary arpeggiation effect.

Beta testing is currently open, so [hit me up](mailto:dominic.fox@gmail.com) if you want to try it.
