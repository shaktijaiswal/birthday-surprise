# Happy Birthday Website 💌

A personal birthday website built from your photos — a scrapbook-style love letter with a photo gallery, a "make a wish" cake, and a spot for your song.

## What's inside
```
├── index.html          → the whole website
├── images/              → your 19 photos (already resized & compressed)
└── assets/
    └── (add love-song.mp3 here)
```

## 1. Add your song (important)
I couldn't include an actual song file (copyright), so the player is ready but silent until you add one:

1. Get an MP3 of the song you want (from a site where you're allowed to download it, or export one you own).
2. Rename it exactly to: `love-song.mp3`
3. Put it inside the `assets` folder.
4. Open the site and tap the ♪ button (top right) — it will start playing.

If you skip this step, the site still works perfectly — the music button just won't play anything.

## 2. Preview it on your computer
Just double-click `index.html` — it opens in your browser. No install needed.

## 3. Put it on GitHub & get a shareable link (GitHub Pages) — step by step

**Step 1 — Create a GitHub account (skip if you already have one)**
Go to [github.com](https://github.com) → Sign up → verify your email.

**Step 2 — Create a new repository**
1. Click the **+** icon (top right) → **New repository**.
2. Name it something like `happy-birthday-love` (no spaces).
3. Set it to **Public**.
4. Do NOT check "Add a README" (you already have one).
5. Click **Create repository**.

**Step 3 — Upload your files**
1. On the new (empty) repo page, click **"uploading an existing file"** (or "Add file" → "Upload files").
2. Drag and drop everything from this folder into the upload box: `index.html`, the `images` folder, the `assets` folder, and `README.md`.
   - If GitHub doesn't let you drag a whole folder, first zip your `images` folder is NOT needed — GitHub keeps folder structure as long as you drag the folder itself, not just files. Most browsers support dragging folders directly onto the upload box.
3. Scroll down, add a message like "first upload", click **Commit changes**.

**Step 4 — Turn on GitHub Pages**
1. In your repo, click **Settings** (top menu).
2. In the left sidebar, click **Pages**.
3. Under "Build and deployment" → **Source**, choose **Deploy from a branch**.
4. Under "Branch", choose **main** and folder **/(root)**, then click **Save**.
5. Wait about 1 minute, then refresh the Pages settings screen.

**Step 5 — Get your live link**
GitHub will show a message like:
> Your site is live at `https://your-username.github.io/happy-birthday-love/`

That link is your website — open it to check everything looks right, then copy and send it to him. 🥂

**If a photo or the page looks broken:** double-check the `images` and `assets` folders uploaded correctly (they should appear as actual folders in your repo, not missing). If needed, delete the repo and redo Step 3, making sure the folders come along.

## Notes
- Everything is editable — open `index.html` in any text editor, all the Hinglish messages are plain text near the top of the `<body>` section, easy to tweak.
- Photos are already compressed for fast loading; the whole site is under ~4MB excluding the song.
