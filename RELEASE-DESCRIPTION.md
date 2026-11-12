# PEQdB Studio Mini 0.2.26 — public playtest

Unofficial PEQdB companion for Chrome and Firefox on macOS and Windows.

**[Download Chrome ZIP](https://github.com/ogjuggy/PEQDBSTUDIOBROWSEREXTENSION/releases/download/v0.2.26/peqdb-mini-chrome.zip)** · **[Download Firefox ZIP](https://github.com/ogjuggy/PEQDBSTUDIOBROWSEREXTENSION/releases/download/v0.2.26/peqdb-mini-firefox.zip)**

Use these packaged browser files; GitHub's automatically generated Source code ZIP contains the repository files.

- **Chrome / Edge / Brave:** `peqdb-mini-chrome.zip`. Extract it, open your browser's extensions page, enable Developer mode and Load unpacked.
- **Firefox 142+:** `peqdb-mini-firefox.zip` or the identical `.xpi`. Open about:debugging → This Firefox → Load Temporary Add-on. This unsigned test build is temporary.
- **Source and notices:** `peqdb-mini-source.zip` contains the full extension source, build tools and third-party notices.
- **Checksums:** `SHA256SUMS.txt` identifies the uploaded files.

Includes browser-audio EQ, Quick Compare, built-in/imported target curves, 2–12-target blind tests, saved EQ presets and a local music player with waveform/spectrum tools and guided listening passages.

0.2.26 adds independent spectrum response settings beside the FPS controls. Default remains 60 FPS / Standard. Fast and Fastest trade bass resolution for faster visual reaction; the readout separates drawn frames and advancing-audio FFT updates. Actual rates depend on browser, display and audio buffering.

Known limits: developer/temporary installation; protected/inaccessible media may not process; physical 144–600 Hz display rendering and broader Windows hardware testing remain to verify. Chrome/Firefox focused checks, numerical/security tests, archive scans and reproducible browser rebuilds pass.

Local music and test results remain local. The extension uses broad website access for page audio and fetches/caches the PEQdB catalogue. This project is not affiliated with or endorsed by PEQdB.
