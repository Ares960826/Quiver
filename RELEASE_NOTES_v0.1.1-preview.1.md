# Quiver v0.1.1 Community Preview

Quiver is a local-first prompt manager and reusable template launcher for
macOS. This preview is a manual upgrade from the local Alpha and from the first
Community Preview.

## What changed

- Slightly wider launcher so long prompt titles and metadata have more room
- Single-line Settings labels in English and Chinese
- Adaptive Rendering selector that no longer overlaps translated text
- `Control+Command+Space` as the default summon shortcut for new installations
- New multilingual showcase and practical Capture / AI Agent library tips

Existing custom shortcuts are preserved. If an older installation already
uses another shortcut, choose the new combination in Settings if desired.

## Download

- `Quiver_0.1.1_aarch64.dmg` — Apple Silicon Macs
- `Quiver_0.1.1_x64.dmg` — Intel Macs
- `SHA256SUMS.txt` — SHA-256 checksums

## Moving from Quiver Alpha

The local Alpha uses a separate app identity and a loopback-only test update
server. It cannot update itself into this public Preview. Quit Quiver Alpha,
install `Quiver.app` from the matching DMG, and keep using the same Prompt
folder. Public Preview updates remain manual for now.

## macOS security notice

This preview is ad-hoc signed and is not notarized by Apple. After moving
Quiver to Applications, try to open it once. If macOS blocks it, open
**System Settings → Privacy & Security**, choose **Open Anyway**, and confirm
**Open**.

Please report reproducible problems through GitHub Issues after removing any
private prompt text, personal paths or sensitive screenshots.
