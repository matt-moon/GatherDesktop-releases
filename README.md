# Piano Gather — releases

Installers and the auto-update feed for **Piano Gather**, the Electron desktop client for
Sonatina's Gather sessions.

This repository holds **build artifacts only**. The source is private.

## Download

Get the latest `.dmg` from [Releases](../../releases/latest).

**macOS (Apple Silicon).** There is no Intel or Windows build yet.

### Before your first session

Grant **Screen Recording** to Piano Gather in
*System Settings → Privacy & Security → Screen & System Audio Recording* **before** you join a
session. macOS can't give the permission to an app that is already running, so granting it
mid-call forces a "Quit & Reopen" and drops you out of the room in front of everyone. You can
add the app with the `+` button before it has ever asked.

## Updates

The app checks for updates on launch and every six hours, downloads in the background, and asks
once whether to restart. It never interrupts you while you are in a session; a deferred update
installs the next time you quit.
