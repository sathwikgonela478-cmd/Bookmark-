# ChatGPT Bookmarks

A small mobile-first Progressive Web App (PWA) for saving ChatGPT conversation links.

## Features
- 10+ bookmarks (no fixed limit)
- Add, edit, delete, and search
- One-tap open of the saved conversation URL
- Local browser storage on this device
- JSON export/import backup
- Installable to Android home screen when hosted over HTTPS

## Use
1. In ChatGPT, open a conversation and use Share → Copy link.
2. Open this app and tap Add.
3. Enter a name and paste the conversation link.
4. Tap Open whenever you want to return to that conversation.

## Install on Android
Host these files on an HTTPS static host (for example GitHub Pages). Open the hosted URL in Chrome, then use Chrome menu (⋮) → Add to Home screen / Install app.

## Important
- Bookmarks are stored in this browser on this device, not automatically synced with ChatGPT or other devices.
- The ChatGPT app may open the conversation link if Android has it set to handle ChatGPT links; otherwise it opens in the browser.
- This is not an extension injected inside ChatGPT. ChatGPT does not provide a public interface for third-party apps to add a custom bookmark panel inside its Android app.
