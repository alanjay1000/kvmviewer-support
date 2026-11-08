# Privacy Policy – KVM Viewer and KVM Clip Helper

_Last updated 8 November 2026_

KVM Viewer (macOS, iOS, iPadOS) and KVM Clip Helper (macOS) are made by Alan Jay ("we"). They are tools
for controlling a computer through your own GL.iNet GLKVM (or other kvmd-based IP KVM) and for moving
your clipboard between your own machines.

## What the apps do with data

**We do not collect, store, sell or share any personal data.** There are no analytics, no advertising
identifiers, no tracking, and no accounts with us.

The apps handle the following data only on your devices and only to do their job:

- **KVM credentials and GL.iNet cloud credentials** – stored in the device Keychain. With iCloud
  Keychain enabled they sync between your own Apple devices through Apple's encrypted service. They are
  sent only to your KVM or to GL.iNet's cloud service when you choose cloud access (GL.iNet's own
  privacy policy applies to that service).
- **Connection settings** (KVM address, names, preferences) – stored on the device and, if you use
  iCloud, in your private iCloud key-value store so your other devices get the same settings.
- **Clipboard contents** (text and images) – sent between KVM Viewer and KVM Clip Helper only. They are
  encrypted end to end (Curve25519 key agreement, ChaCha20-Poly1305) and travel over your local
  network, or through your own private iCloud database when the two machines are not on the same
  network. Clips expire from iCloud after a few minutes. We never see them.
- **Remote Mac password** (optional feature) – stored in the Keychain protected by Touch ID / Face ID
  and typed onto the remote machine only when you ask; it is never displayed and never leaves the device
  other than as keystrokes to your KVM.
- **Screen text recognition** – performed entirely on the device with Apple's Vision framework.

## Permissions

- **Local Network** – to find the KVM with Bonjour and for the encrypted clipboard link.
- **iCloud** – optional, for settings sync and the clipboard relay between your own devices.
- **Notifications (background)** – silent iCloud change notifications only; nothing is shown.

## Third parties

The only third-party service the apps can talk to is GL.iNet's cloud relay, and only when you choose to
connect through it. See GL.iNet's privacy policy for that service.

## Children

The apps are not directed at children and collect no data from anyone.

## Changes and contact

If this policy changes, the new version will be published at the same address. Questions:
feedback@sqigg.com.
