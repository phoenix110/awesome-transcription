# Awesome Transcription [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of speech-to-text tools — desktop apps, APIs, open-source models, and services for turning audio and video into usable text.


Whisper changed what transcription costs and what it can do. This list covers the local apps built on top of it, the hosted APIs that scale past a laptop, the open-source models underneath, and the editor-first tools that treat the transcript as the timeline.


## Contents


- [Open Source Models & Libraries](#open-source-models--libraries)
- [Desktop Apps](#desktop-apps)
- [Web Apps & Services](#web-apps--services)
- [Speech-to-Text APIs](#speech-to-text-apis)
- [Meeting Recorders & Notetakers](#meeting-recorders--notetakers)
- [Subtitling & Video Editing](#subtitling--video-editing)
- [Benchmarks & Reading](#benchmarks--reading)
- [Contributing](#contributing)


---


## Open Source Models & Libraries
*The models most of this list is built on.*


* [faster-whisper](https://github.com/SYSTRAN/faster-whisper) - Reimplementation of Whisper using CTranslate2, substantially faster with lower memory use.
* [NVIDIA NeMo](https://github.com/NVIDIA/NeMo) - Toolkit including Parakeet and Canary ASR models that top several accuracy leaderboards.
* [Vosk](https://alphacephei.com/vosk/) - Lightweight offline speech recognition supporting many languages on modest hardware.
* [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Plain C/C++ port of Whisper that runs efficiently on CPU and Apple Silicon.
* [Whisper](https://github.com/openai/whisper) - OpenAI's open-source multilingual speech recognition model, the basis for much of this category.
* [WhisperX](https://github.com/m-bain/whisperX) - Whisper with forced alignment for accurate word-level timestamps and speaker diarization.


## Desktop Apps
*Local-first transcription without uploading your audio anywhere.*


* [Aiko](https://sindresorhus.com/aiko) - Free Mac and iOS transcription app running Whisper entirely on-device.
* [Hello Transcribe](https://www.hellotranscribe.com) - On-device transcription for iOS and macOS with no server round-trip.
* [MacWhisper](https://goodsnooze.gumroad.com/l/macwhisper) - The most widely used Mac Whisper front-end, with batch processing, diarization, and subtitle export.
* [Superwhisper](https://superwhisper.com) - Mac dictation and transcription app focused on voice-driven text input across applications.
* [Vibe](https://thewh1teagle.github.io/vibe/) - Open-source cross-platform transcription app for macOS, Windows, and Linux.


## Web Apps & Services
*Upload a file, get a transcript, no install.*


* [Happy Scribe](https://www.happyscribe.com) - Transcription and subtitling with a human-review tier, aimed at media and research teams.
* [Local Video Text](https://localvideotext.com/) - Browser-based English transcription for one local MP4, WebM, or MOV file; processing stays in the browser.
