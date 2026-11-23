# Glidedesk

**Glidedesk** is a fast remote desktop app for iPhone and iPad that connects to your Mac's built-in Screen Sharing, at home or anywhere through Tailscale. **Glidedesk Helper** is its free companion app for the Mac.

**[Download Glidedesk Helper for Mac](https://github.com/jabol183/Glidedesk-Helper/releases/latest/download/Glidedesk-Helper.zip)** (macOS 14 or later, signed and notarized by Apple)

## What the helper does

- **Fast video.** macOS Screen Sharing sends the screen slowly to apps other than Apple's own. The helper streams it as smooth, hardware-compressed video instead. Keyboard, mouse and clipboard still go through Screen Sharing.
- **Private screen.** While you're connected, the Mac's own display shows a grey "in use remotely" screen, so people near the Mac can't see what you're doing. You can turn this off in the menu.
- **Smart keyboard.** The iPhone keyboard opens when you click into a text field on the Mac.
- **Fits your screen.** On a Mac with no monitor (a headless Mac mini), the Mac's display takes the shape of your iPhone or iPad while you're connected.

Glidedesk works without the helper too, using plain Screen Sharing; the helper just makes it much faster.

## Install the helper

1. Download and unzip **Glidedesk Helper**, then move it to your **Applications** folder.
2. Open it. A setup window walks you through:
   - **Screen Sharing** (System Settings → General → Sharing)
   - **Screen & System Audio Recording** permission, for the fast video
   - **Accessibility** permission, for the smart keyboard
3. Connect from Glidedesk on your iPhone or iPad. The ⌘ menu shows **Fast video: on**.

The helper starts automatically with your Mac and lives in the menu bar. It tells you when an update is available.

## Support

Questions, problems or ideas: [open an issue](https://github.com/jabol183/Glidedesk-Helper/issues/new). Please include your iPhone/iPad model, your macOS version and what you were doing.

**Common fixes**

- *Can't connect:* make sure Screen Sharing is on and your Mac user is allowed under its ⓘ button, and that the Mac isn't asleep (Energy settings: prevent automatic sleeping, wake for network access).
- *"Fast video: not available":* open Glidedesk Helper's setup window from its menu bar icon and allow Screen Recording, then quit and reopen the helper.
- *Away from home:* install Tailscale on the Mac and the iPhone, and use the Mac's Tailscale address in Glidedesk.

## Privacy

See the [privacy policy](PRIVACY.md). In short: Glidedesk and its helper collect no data, have no accounts, no analytics and no ads.

## Security

- The video is only sent to a device that has signed in to your Mac's Screen Sharing with a Mac user name and password. The helper passes that sign-in straight to macOS; it never sees or stores your password.
- The helper only accepts connections from your local network and Tailscale (private and CGNAT addresses). Ports: 5950, 5952, 5953.
