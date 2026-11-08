---
title: KVM Viewer – Support
---

# KVM Viewer & KVM Clip Helper

**KVM Viewer** is a native macOS, iOS and iPadOS front end for GL.iNet GLKVM devices (Comet, Comet PoE)
and other kvmd-based IP KVMs. **KVM Clip Helper** is its companion menu-bar app for the Mac that is
plugged into the KVM; together they sync the clipboard – text and images – end to end encrypted.

## Getting started
1. Install KVM Viewer on your Mac, iPhone or iPad. Open Settings (⌘,) and either pick your KVM from the
   list (same network) or sign in to your GL.iNet cloud account and choose the device.
2. Enter the KVM's admin password once; it is kept in the Keychain and follows you to your other
   devices through iCloud Keychain.
3. Optional: install KVM Clip Helper on the computer behind the KVM (if it's a Mac). Open its menu,
   copy the pairing code, and paste it into KVM Viewer › Clipboard › Clipboard Sync…. With iCloud on
   both machines the pairing happens by itself.

## Keyboard
- **PC | Mac** switch: on a PC target ⌘C/⌘V/⌘Z… are sent as Ctrl shortcuts; on a Mac target ⌘ passes through.
- Send Keys menu: Ctrl‑Alt‑Del, Alt‑Tab, Win+L, Linux consoles, Mission Control, remote Mac screenshots.
- iPhone/iPad: the Keyboard button types onto the remote; Zoom & Pan enlarges the picture without moving the remote mouse.

## Video
The app picks the KVM's transfer mode automatically (WebRTC Native → FEC → WebRTC) and restarts the
stream if frames stop. Connection › Video Transfer pins a mode. The KVM page's own bars are hidden;
the KVM Bars button (⌃⌘B) brings them back.

## Troubleshooting
- **"Session terminated"** – GL.iNet's free cloud plan allows one session per device at a time. Close
  the other viewer, then Reconnect (⌃⌘K).
- **No video** – Connection › Restart Video Stream (⌃⇧⌘R). If it keeps happening, try pinning WebRTC (FEC).
- **Clipboard not arriving** – check the traffic light in Clipboard Sync; "Restart Sync" after changing
  networks; both apps show their build number – keep them on the same build.
- **Local Network permission** – macOS/iOS ask once; it is needed to find the KVM and for the LAN clipboard link.

## Privacy
We collect nothing. See the [privacy policy](privacy.html).

## Contact
feedback@sqigg.com
