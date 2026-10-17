<p align="center"><img src="logo-juggler.svg" width="120" alt="JUGGLER"></p>

# JUGGLER

A keyboard-driven music scheduler for radio. JUGGLER builds the day's music log from your
library, clocks and rules, explains every choice it makes, and lets you edit the result by hand,
all from the keyboard in a fast, DOS-style screen.

This repository holds the published builds. Download them from
[Releases](https://github.com/airadiolabs/juggler-releases/releases).

## Downloads

| System | File |
|---|---|
| Linux, x86_64 | `juggler-<version>-linux-x86_64.tar.gz` |
| Linux, ARM64 | `juggler-<version>-linux-arm64.tar.gz` |
| macOS, Apple silicon | `juggler-<version>-macos-arm64.zip` |
| macOS, Intel | `juggler-<version>-macos-x86_64.zip` |
| Windows, x86_64 | `juggler-<version>-windows-x86_64.zip` |

## First launch

The alpha builds are not code-signed yet.

- **Linux:** unpack, then run `./splus`. `./splus install-desktop` adds JUGGLER to the app grid.
- **macOS:** unzip and move `JUGGLER.app` to Applications. The first time, right-click it and
  choose **Open**, then **Open** again (or allow it under System Settings → Privacy & Security).
- **Windows:** unzip and run `juggler.exe`. If SmartScreen appears, choose **More info** →
  **Run anyway**.

Your stations are kept in `~/.local/share/splus` (Linux), `~/Library/Application Support/splus`
(macOS) or `%APPDATA%\splus` (Windows).

## Status

Alpha: for testing, not yet for running a station on air. Please report problems in
[Issues](https://github.com/airadiolabs/juggler-releases/issues).
