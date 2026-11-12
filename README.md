# PEQdB Studio Browser Extension

An unofficial PEQdB companion for Chrome and Firefox. Apply EQ to browser audio, save presets, compare target curves and run blind listening tests using browser playback or your own music.

Includes a local music player with waveform and spectrum tools for preparing personal listening tests.

**Early prototype — shared for testing and feedback.** Features and UI are still being developed, so expect bugs and rough edges. Suggestions and bug reports are welcome.

## Downloads

**[Download for Chrome / Edge / Brave](https://github.com/moondropquarksenjoyer/peqdb-studio-extension/releases/download/v0.2.26/peqdb-mini-chrome.zip)**

**[Download for Firefox](https://github.com/moondropquarksenjoyer/peqdb-studio-extension/releases/download/v0.2.26/peqdb-mini-firefox.zip)**

[View the v0.2.26 release](https://github.com/moondropquarksenjoyer/peqdb-studio-extension/releases/tag/v0.2.26)

These are manual-install playtest builds. Download the browser file above; GitHub’s **Code → Download ZIP** is not the extension package.

## Features

- Parametric EQ for accessible browser audio and local music.
- PEQdB headphone measurements, target curves and AutoEQ.
- Live filter editing and saved EQ presets.
- Quick comparisons between built-in or imported target curves.
- Blind preference tests with pools of 2–12 targets.
- Local music playback, playlists and individual song imports.
- Zoomable waveforms, spectrum analysis and guided listening-passage preparation.
- Toolbar controls, a docked sidebar/side panel and an optional separate window.

## Installation

### Chrome, Edge and Brave

1. Download **peqdb-mini-chrome.zip** and extract it.
2. Open your browser’s extensions page:
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
   - Brave: `brave://extensions`
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the extracted folder that directly contains `manifest.json`.
6. Pin the extension from the puzzle-piece menu.
7. Reload any already-open music or video pages.

Keep the extracted folder in place after installing.

### Firefox

Requires **Firefox 142 or newer**.

1. Download **peqdb-mini-firefox.zip** without extracting it.
2. Open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on…**.
4. Select the downloaded ZIP.
5. Pin the extension from the puzzle-piece menu.
6. Reload any already-open music or video pages.

**The Firefox build is unsigned and temporary. Load it again after restarting Firefox.**

## Getting started

The first launch downloads the headphone catalogue.

1. Start playback on a supported page, or open **Music → Add songs**.
2. Select your headphone measurement and a target.
3. Run **AutoEQ**, or edit filters manually.
4. Save your settings as an EQ preset.

Use **Quick Compare** to switch between targets. Choose **Blind test** to compare without seeing target identities.

For repeatable excerpts from local music, open **Music → Prepare passages**. Preparation is optional—you can also test the current song directly.

Choose **··· → Dock in browser** for controls that stay open, or **Pop out** for a resizable window.

## Spectrum settings

The default is **60 FPS / Standard response**.

- **Maximum spectrum FPS** controls the requested drawing and update rate.
- **Spectrum response** selects Standard, Fast or Fastest. Faster modes react sooner but lose some bass-frequency detail.

The optional readout separates drawn FPS from fresh spectrum updates. Actual rates depend on your display, browser and audio device.

## Testing notes

- Start at a low listening volume. Audio bugs may cause unexpected level changes, distortion or dropouts.
- If playback goes silent, pause it before raising the volume.
- Export your EQ presets before updating or removing the extension.
- Some websites, protected media and audio formats may not work.
- The extension requests broad website access to process accessible page audio.

Local music and listening results stay on your device. Headphone catalogue and target data are fetched from PEQdB and cached locally.

## Feedback

[Report a bug or suggest a feature](https://github.com/moondropquarksenjoyer/peqdb-studio-extension/issues)

For bugs, include your browser version, operating system, steps to reproduce and whether you were using browser audio or local music.

## Attribution

This is an unofficial project, not affiliated with or endorsed by PEQdB.

The extension uses AutoEQ C/WASM and other third-party components. Their source and license notices are included in the release’s extension source package.
## License

This project is licensed under the [MIT License](LICENSE).
