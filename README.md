# kopfkino

Kopfkino is a library providing syntactic sugar sprinkled on top of MoviePy and AI components, to allow authoring of simple human-friendly video scripts.

> 🚧 **Work in progress, code is coming.**

Kopfkino (German, ˈkɔpfˌkiːno) roughly translates to "movie theater of your mind", describing a kind of daydreaming when your imagination produces vivid images right in your head. It addresses the main purpose of this project — give you a convenient way to convert your ideas into movie scripts (which are also Python scripts), for producing e-learning videos and such, using an expressive [DSL](https://en.wikipedia.org/wiki/Domain-specific_language).

It enables you to concentrate on your content and its timeline, hiding away most of the technical details and quirks of underlying packages doing the grunt work, like [MoviePy](https://pypi.org/project/moviepy/).

## Features

Major functions and use-cases:
 * Rough and final cut of your recordings.
 * Adding a title screen and end credits.
 * Adding subtitles, optionally also converted to audio via an AI voice (TTS / text to speech).
 * Using audio loops for background music.

 There is an [early proof of concept](https://youtu.be/ZAGDNwk7Bd8?si=2dRlIfLR_fYQENB9) on YouTube, to give you an idea of the end result.


 ## Related Projects & Services
  * [Open Broadcaster Software (OBS Studio)](https://obsproject.com/) — Multi-platform software for video recording and live streaming.
  * [Ideogram](https://ideogram.ai/) — My recommendation for generating still images from a text prompt, to e.g. use in intro and outro sequences of a video.
  * [MoviePy](https://pypi.org/project/moviepy/) — A Python library for video editing: cutting, concatenations, title insertions, video compositing (a.k.a. non-linear editing), video processing, and creation of custom effects.
  * [coqui-ai/TTS](https://github.com/coqui-ai/TTS) — A deep learning toolkit for Text-to-Speech, battle-tested in research and production.
  * [pydub](https://pypi.org/project/pydub/) — Manipulate audio with an easy to use interface.