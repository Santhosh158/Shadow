# Shadow · Field Guide — PWA

A force-free training companion for a fearful Belgian Malinois. Installable web app: works offline, opens fullscreen, saves your logs on your device.

## What's in this folder
- `index.html` — the app
- `manifest.json` — makes it installable
- `sw.js` — service worker (offline support)
- `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`, `apple-touch-icon.png` — app icons

Keep all files together in the same folder. Don't rename `index.html`.

---

## How to host it free on GitHub Pages

You only do this once. After that, the link is permanent and you just tap the home-screen icon.

### 1. Make a GitHub account
Go to github.com and sign up (free) if you don't have one.

### 2. Create a new repository
- Click the **+** (top right) → **New repository**
- Repository name: `shadow` (or anything)
- Set it to **Public**
- Click **Create repository**

### 3. Upload these files
- On the new repo page, click **uploading an existing file** (the link in the middle), or **Add file → Upload files**
- Drag in **all the files from this folder** (index.html, manifest.json, sw.js, and all the .png icons) — upload them together
- Scroll down, click **Commit changes**

### 4. Turn on GitHub Pages
- In the repo, click **Settings** (top menu)
- Left sidebar → **Pages**
- Under **Branch**, choose **main** and **/ (root)**, then click **Save**
- Wait ~1 minute. The page will show a link like:
  `https://YOURNAME.github.io/shadow/`

### 5. Open it on your phone in Safari
- Open that link in **Safari** (not in-app browsers)
- It should load the app. Test the tabs (Today / Train / Signals / Plan / Log)

### 6. Install to your home screen
- Tap the **Share** button (square with up-arrow)
- **Add to Home Screen** → name it "Shadow" → Add
- Done. Tap the paw icon any time — it opens fullscreen like a real app, even offline.

---

## Notes
- **Your data (logs, checkboxes, milestones) is saved on your phone**, tied to this web address. Use the same link / home-screen icon each time and it persists.
- To update the app later, just re-upload a new `index.html` to the repo (Add file → Upload files → commit). The link stays the same.
- The first load needs internet (to cache the app + fonts). After that it works offline.
- If you ever clear Safari's website data, the saved logs for this site are cleared too — occasional screenshots of your Log tab are a cheap backup.
