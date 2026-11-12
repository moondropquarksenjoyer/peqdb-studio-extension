## Very early prototype

This is an experimental playtest build. Expect bugs, unfinished features and changes between versions. It is not ready for everyday, dependable use.

- **Start at a low listening volume.** Audio bugs may cause unexpected level changes, distortion or dropouts. If playback goes silent, avoid turning the volume up—it could resume unexpectedly.
- **Back up your EQ presets before updating.** Settings, music-library links and saved results may need to be restored or recreated.
- **Browser support varies.** Some websites, protected media and audio formats may not work correctly.
- **Review the permissions.** The extension requests broad website access to process browser audio.
- **Installation is currently manual.** Chrome uses developer mode; the unsigned Firefox build must be loaded again after restarting Firefox.

This is an unofficial project, not affiliated with or endorsed by PEQdB. Feedback and bug reports are welcome.



## Installation

### Chrome, Edge and Brave

[**Download Chrome ZIP**](https://github.com/ogjuggy/PEQDBSTUDIOBROWSEREXTENSION/releases/download/v0.2.26/peqdb-mini-chrome.zip)

1. Download and extract the ZIP.
2. Open `chrome://extensions` — or `edge://extensions` / `brave://extensions`.
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the extracted folder containing `manifest.json`.
5. Pin the extension from the puzzle-piece menu.
6. Reload any already-open music or video pages.

Keep the extracted folder in place after installing.

### Firefox

[**Download Firefox ZIP**](https://github.com/ogjuggy/PEQDBSTUDIOBROWSEREXTENSION/releases/download/v0.2.26/peqdb-mini-firefox.zip)

Requires **Firefox 142 or newer**.

1. Download the ZIP without extracting it.
2. Open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on…** and select the downloaded ZIP.
4. Pin the extension from the puzzle-piece menu.
5. Reload any already-open music or video pages.

**This unsigned playtest build is temporary. You must load it again after restarting Firefox.**

### First use

The first launch downloads the headphone catalogue. Start playback, select your headphone and target, then run **AutoEQ**.

For local music, open **Music → Add songs**. For controls that stay open, choose **··· → Dock in browser**.
