# LineThru Changelog

## 1.1.0 — 2026-07-10

## LineThru 1.1.0

- All-new low-latency audio engine for hardware monitoring. Input and output now run in a single realtime audio cycle on a drift-compensated device pair — no more crackling, in any latency mode.
- Latency modes got dramatically faster: Low Latency now runs 2.7 ms buffers (previously ~5.3 ms buffers over a much slower transport), Balanced 5.3 ms, Higher Stability 10.7 ms. Playing an instrument through Low mode now feels immediate.
- Fixes intermittent crackling/dropouts when monitoring hardware inputs, especially with input and output on different USB devices.


## 1.0.5 — 2026-07-10

## LineThru 1.0.5

- Added physical input latency settings with Low Latency, Balanced, and Higher Stability modes.
- Latency preferences are saved automatically and applied when monitoring microphones, instruments, audio interfaces, and other input devices.


## 1.0.4 — 2026-07-09

## LineThru 1.0.4

- License management moved to a dedicated About window. Once your Mac is activated, the main window stays focused on monitoring — no more License section taking up space.
- The new About window (LineThru → About LineThru) shows your license status and the Deactivate button, plus the app version and links to linethru.app and support.


## 1.0.3 — 2026-07-08

Maintenance release.

- Verifies the in-app update flow end to end.


## 1.0.2 — 2026-07-08

Maintenance release.

- Fixes in-app updates failing with "An error occurred while running the updater."


## 1.0.1 — 2026-07-08

Maintenance release.

- Downloads now ship as a disk image (DMG) for smoother installs.
- Under-the-hood improvements to the in-app updater and release process.


## 1.0.0 — 2026-07-08

Initial release.

- Monitor any hardware input (line-in, interface) with level, balance, and mute controls and live meters.
- Route a single Mac app's audio to the output of your choice — everything else keeps playing normally.
- Hardware-style interface in the main window and the menu bar.
- Try before you buy: unlicensed, monitoring runs for 60 seconds at a time.

Buy a license at [linethru.app](https://linethru.app).
