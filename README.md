# NSEScope — Binary Releases

Prebuilt Linux and Windows binaries for **NSEScope**, an Nmap + NSE
authorized vulnerability assessment desktop app.

This repository intentionally contains **no source code** — it exists only
to host release binaries. See the [Releases](../../releases) tab for
downloads.

## Downloads (latest release)

| Platform | File |
|---|---|
| Linux (x86_64) | `nsescope-linux-amd64.tar.gz` |
| Windows (x86_64) | `NSEScope-Setup-amd64.exe` (installer) or `nsescope-windows-amd64.zip` (portable) |

## Requirements

- **Linux**: `libgtk-3-0`, `libwebkit2gtk-4.1-0` (or `-4.0-37`), and `nmap`.
- **Windows**: [Nmap for Windows](https://nmap.org/download.html) (with
  Npcap for raw scans), and the WebView2 runtime (bundled with modern
  Windows, or auto-installed by the installer).

Windows builds are cross-compiled and have not been validated on physical
Windows hardware. The installer is not code-signed, so SmartScreen may warn
on first run.
