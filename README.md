# TIK

A compact project clock, task checklist, spectrum and monitoring plugin.

[Download TIK 0.4.0 beta](https://github.com/mrjellifish/TIK-releases/releases/tag/v0.4.0-beta.1)

**macOS Apple Silicon · AU + VST3 · 400×200 interface**

Expand the ZIP and open **TIKUpdater.app**. Save your session and close DAWs first; installation retains previous bundles. Rescan plugins after installation if needed.

TIK also appears in compatible family plugins: click their logo, open **Plugins**, then **Check**.

This beta is ad-hoc signed and not Apple notarized. macOS may require approval in **System Settings → Privacy & Security** after you verify the download source. Do not disable Gatekeeper globally. Intel and Windows builds are not available.

Features include lifetime/session tracking, local project recovery, task notes, palette-linked spectrum, stereo meters, selectable LUFS-M/integrated LUFS-I, project details, CSV export, task archive/history analytics and an optional 0 dBFS sample-peak limiter. The limiter is off by default. Manual time corrections and analytics/export are future work.

Report beta issues in this repository, including your macOS version, DAW and plugin format. Never upload private DAW sessions or your local project-memory database.

The 0.4.0 database upgrade preserves a `.pre-v4.sqlite3` backup. Older binaries cannot read schema 4; see the release notes before downgrading.
