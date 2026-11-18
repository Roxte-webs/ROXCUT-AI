# ROXCUT AI Pro Studio — Mobile-first editing prototype

A local-first, mobile-friendly browser editor with a professional dark multi-panel workspace. This is a working prototype, not a full CapCut/After Effects replacement.

## Open it
- Extract the ZIP.
- Open `index.html` in a modern desktop/mobile browser, or serve the folder with `python3 -m http.server 8000` and open port 8000.
- For best compatibility, use a modern Chromium browser. Some mobile browsers limit MediaRecorder, canvas capture, local media codecs, or large-file processing.

## Features that currently work
- Import video and audio files from device; drag/drop files onto preview on desktop.
- Video preview and timeline.
- Sequential clip timeline with trim-in/out, split at playhead, duplicate and delete.
- Playback, playhead seeking and timeline zoom.
- Aspect-ratio presets: 16:9, 9:16, 1:1, 4:5.
- Text overlays with timing, size, color, stroke, position, bold and shadow.
- Caption overlay sample and caption style selection.
- Background music import and playback.
- Video speed, volume, brightness, contrast, saturation, warmth and blur controls.
- Color presets.
- Effect toggles and effect stack UI.
- AI style/mood/intensity prompt panel and locally generated edit plan.
- Script-outline helper and caption sample helper.
- Project JSON download.
- WebM export using browser MediaRecorder.

## Limitations
- The AI panel currently produces a local, rule-based editing plan. It does not analyze video contents or call a real AI model.
- Export is browser-based WebM and runs in real time. Codec, audio, resolution, performance and file size vary by browser/device.
- Export is a prototype renderer; multi-clip rendering, advanced transitions and effect stack parity are incomplete.
- Speech-to-text, Hinglish captions from speech, automatic highlight detection, silence detection, beat analysis, automatic phonk editing, keyframes, motion tracking, masking, stabilization, AI noise reduction, voice changers, TTS, and advanced compositing are not implemented yet.
- No cloud service or API key is included. Media is handled locally in the browser.

## Development
This version uses plain HTML/CSS/JavaScript and has no build dependencies.
