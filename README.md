# Remembr

A home-screen web app for iPhone: birthday reminders with drafted messages, and monthly "new month" messages with shuffled versions sent to your contacts.

## Put it on GitHub Pages
1. Create a new repository and upload everything in this folder to the root (`index.html`, `manifest.webmanifest`, `sw.js` and the three PNG icons).
2. In the repo go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
3. After a minute the app is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Add it to your iPhone
Open the link in Safari, tap Share, then **Add to Home Screen**.

## Your data
Birthdays, recipients and settings are stored on your phone only (browser storage for that link), never in the repo. Use **? → Back up (copy)** to save a copy to Notes and **Restore** to load it on a new phone or link. If you host on a public repo, anyone with the link can open the app, but they only see their own data.

## Updating
Edit `index.html` in the repo and commit. The app checks for the latest version each time it opens and falls back to the saved copy when offline.

## Sending new-month messages
Tap **Message next** or **Send** on a row to open Messages ready to send. For bulk, create a Shortcut named **Remembr Send** (steps are in the app under New month) and use **Send all via Shortcut**.
