# RoxCut AI — Prototype 0.1

A mobile-first, browser-based gaming video editing prototype. This is a static app: no build step, server, API key, or framework installation is required.

## Features in this prototype
- Import and preview a video
- Play/pause, seek, and display time
- Trim start/end and preview the trim range
- Editing style cards and a local style-plan generator
- Manual caption overlay with Classic, Gaming, Phonk, Minimal, and Meme styles
- Text overlay, colour and size controls
- Preview zoom and shake effects
- Add background music, preview it, set source/music volume
- Brightness, contrast, saturation, warmth, and colour presets
- Export a real-time WebM render using browser MediaRecorder and canvas
- Local browser processing; media is not uploaded to a server

## Limitations
- Auto-edit plan is rule-based and does not analyse video contents yet.
- Captions are manually entered; speech recognition and Hinglish transcription are not included yet.
- Effects are preview overlays; zoom/shake are basic.
- Export is real-time and browser-dependent. WebM is the output format. It can be slow and may fail for very long or high-resolution files on mobile.
- Browser capture APIs work best in current Chrome. Keep the page open during export.

## Run locally
Open `index.html` in a modern browser. If using GitHub Pages, publish the repository root.

## GitHub Pages deployment
1. Upload all files to the repository root.
2. Open repository **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)` and save.
5. Wait for the Pages URL to appear.

## Files
- `index.html` — UI and controls
- `style.css` — responsive styling
- `app.js` — editor logic and export
