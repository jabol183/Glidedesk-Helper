# Privacy Policy — Glidedesk and Glidedesk Helper

_Last updated: November 23, 2026_

Glidedesk (for iPhone and iPad) and Glidedesk Helper (for Mac) are made by Lukasz Jabcon. This policy explains what happens to your information when you use them.

## The short version

We don't collect any data. There are no accounts, no analytics, no tracking, no advertising and no servers of ours that your screen, keystrokes or passwords pass through.

## What stays on your devices

- **Saved Macs.** The names, addresses, ports and user names of the Macs you add are stored on your iPhone or iPad.
- **Passwords.** If you choose to save a password, it is stored in the iOS Keychain on that device only (not synced through iCloud), and can be protected with Face ID.
- **Your screen and input.** When you connect, your iPhone or iPad talks directly to your own Mac over your local network or your own VPN (such as Tailscale). The Mac's screen, your keystrokes, pointer movements and clipboard text travel only between your devices.

## Glidedesk Helper (Mac)

- It captures the Mac's screen only while a device that has signed in to the Mac's Screen Sharing is connected, and sends it only to that device.
- It reads which kind of control has keyboard focus (for example "a text field" or "a password field"), never the text in it, and sends only that yes/no information to your connected device.
- It never sees your Mac password: sign-in is handled by macOS Screen Sharing.
- Once a day it downloads a small file from GitHub (`latest.json` in this repository) to see whether a newer version exists. That request contains no information about you beyond what any web request does (such as your IP address, which GitHub handles under its own privacy policy).

## Data shared with third parties

None.

## Children

The apps are not directed at children and collect no personal information from anyone.

## Changes

If this policy changes, the new version will be published at this address with a new date.

## Contact

Open an issue at https://github.com/jabol183/Glidedesk-Helper/issues.
