# AppleVNC Helper for Mac

A free menu bar app for your Mac that makes **AppleVNC** on iPhone and iPad much faster.

**[Download the latest version](https://github.com/jabol183/AppleVNC-Helper/releases/latest/download/AppleVNC-Helper.zip)** (macOS 14 or later, signed and notarized by Apple)

## What it does

- **Fast video.** macOS Screen Sharing sends the screen slowly to apps other than Apple's own. The helper streams it as smooth, hardware-compressed video instead. Keyboard, mouse and clipboard still go through Screen Sharing.
- **Private screen.** While you're connected, the Mac's own display shows a grey "in use remotely" screen, so people near the Mac can't see what you're doing. You can turn this off in the menu.
- **Smart keyboard.** The iPhone keyboard opens when you click into a text field on the Mac.
- **Fits your screen.** On a Mac with no monitor (a headless Mac mini), the Mac's display takes the shape of your iPhone or iPad while you're connected.

## Install

1. Download and unzip **AppleVNC Helper**, then move it to your **Applications** folder.
2. Open it. A setup window walks you through:
   - **Screen Sharing** (System Settings → General → Sharing)
   - **Screen & System Audio Recording** permission, for the fast video
   - **Accessibility** permission, for the smart keyboard
3. Connect from AppleVNC on your iPhone or iPad. The ⌘ menu shows **Fast video: on**.

The helper starts automatically with your Mac and lives in the menu bar. It tells you when an update is available.

## Privacy and security

- The video is only sent to a device that has signed in to your Mac's Screen Sharing with a Mac user name and password. The helper passes that sign-in straight to macOS; it never sees or stores your password.
- It only accepts connections from your local network and Tailscale (private and CGNAT addresses). Ports: 5950, 5952, 5953.
- Nothing is sent anywhere else. The only internet request is a daily check for a newer version on this page.
